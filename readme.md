# Generate trace
```bash
./generate-trace github.com google.co.uk ee.co.uk twitter.com | tee trace.txt
```

# Render graph
```bash
./render-graph < trace.txt | dot -Tsvg  > blah.svg && firefox blah.svg
```

# Dependencies
```bash
sudo apt install graphviz
```
