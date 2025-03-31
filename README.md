# The Challenge

- Losslessly compress `data.bin` such that the combined size of your compressed output and decompressor script is **at least 1 byte smaller** than the original file (1 MiB). This corresponds to a compression ratio of approximately 1.00000095 or better.
- Submit your compressed file `compressed.bin`, along with the decompression script `decompress.py` such that when I run `decompress.py compressed.bin reconstructed.bin`, the reconstructed output is identical to the original data. Also include the SHA256 hash as I did as these should be identical. You can also include the compressor code if you'd like, but it's not necessary. 
- For submission, fork this repo and make a pull request with your files placed in `submissions/{your_username}/`. Or you can e-mail me these zipped files at `impossible_compression_challenge@proton.me`. 

## Reward
I’ll give $10,000 to the first person who achieves a valid compression — even if it’s just 1 byte smaller — under the rules above.