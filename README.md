# codec-base32

Base32 encode and decode for Delphi

Sample encode
```delphi
uses
  Codec.Base32;

begin
  TBase32.Encode('ABCabc123', TEncoding.UTF8);
end;
```

Sample decode
```delphi
uses
  Codec.Base32;

begin
  TBase32.Decode('IFBEGYLCMMYTEMY=', TEncoding.UTF8);
end;
```