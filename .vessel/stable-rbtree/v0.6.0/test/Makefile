default:
	$(shell vessel bin)/moc $(shell vessel sources) -wasi-system-api -o Test.wasm StableRBTreeTest.mo && wasmtime Test.wasm
	rm -f Test.wasm
