# ONT-stuff

Docker image containing some software to process reads from Oxford Nanopore technologies (ONT).

The image contains:
 - Albacore v2.3.3
 - [porechop](https://github.com/rrwick/Porechop) 0.2.4

```bash
# run Albacore
$ docker run -it -v $(pwd):/home/working -w /home/working --rm chrishah/ont-stuff read_fast5_basecaller.py

# run porechop
$ docker run -it -v $(pwd):/home/working -w /home/working --rm chrishah/ont-stuff porechop
```
