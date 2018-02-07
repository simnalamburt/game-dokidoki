Doki Doki Literature Club!
========

이 게임이 그렇게 무섭다면서요?

```bash
# See %APPDATA%\RenPy\DDLC-1454445547

python -c "import zlib; open('persistent.pickle', 'wb').write(zlib.decompress(open('persistent', 'rb').read()))"
python3 -m pickletools persistent.pickle | less

# *.save 파일은 zip파일임. 파일 확장자만 바꾸면 압축이 풀린다.
```

###### Reference
- https://www.renpy.org/doc/html/persistent.html
