https://codefights.com/arcade/intro/level-12/sCpwzJCyBy2tDSxKW

```rb
def messageFromBinaryCode(code)
    code.scan(/[01]{8}/).map{|e| e.to_i 2}.inject '', &:concat  
end
```
