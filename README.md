# Brotli decompressor for Lazarus/FPC

Add SimpleBrotli to your uses, then:

```
  BrotliDecompressFile('alice.br', 'alice.txt');
```

also available:
```
  BrotliDecompressStreams(InStr, OutStr: TStream): Integer;
  function UnBrotli(const Compressed: AnsiString): AnsiString;
```
