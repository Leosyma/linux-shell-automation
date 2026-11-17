# Linux shell automation

Ten scripts under scripts/ cover Linux automation, backups and auditing. The Dockerfile supplies the environment. LEIAME.txt explains scheduling the audit with cron and redirecting its output.

## Run locally

```sh
docker build -t shell-lab .
docker run --rm -it -v "$PWD/scripts:/scripts" shell-lab bash
```
