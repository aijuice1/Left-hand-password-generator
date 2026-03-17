# Left-Hand-Password-Generator ☝

This will auto-generate a 16 character password that can be used with your left hand

Use in your terminal of choice

If you want a 8 or 12 character password - change -c16 to 8 or 12


```bash
</dev/urandom tr -dc '12345!@#$%qwertQWERTasdfgASDFGzxcvbZXCVB' | head -c16; echo ""
```
