# PascalString


supports platform Win32, Win64, OSX, iOS and Android.



## Usage TPascalString

```Delphi

var
  s:string;
  c:Char;
  ps:TPascalString;
  i:Integer;
begin
  ps:='123';
  s:=ps;
  ps:=s;

  s:='';
  for i:=1 to ps.len do
    s:=s+ps[i];

  ps:='';
  for c in s do
    ps:=ps+c;

  ps.Append('456');
  i:=ps.GetPos('234');
end;


```



qq600585
