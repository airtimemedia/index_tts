```
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | bash
apt-get install git-lfs
curl -LsSf https://hf.co/cli/install.sh | bash
pip install WeTextProcessing transformers==4.52.1 modelscope==1.27.0
git lfs pull
hf download IndexTeam/IndexTTS-2 --local-dir=checkpoints
```