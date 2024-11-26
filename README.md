## Digital-Human
Codebase for several Digital-human projects, the dependencies of projects can be downloaded by the correspoinding Readme.md file. And the weights used in each projects can be downloaded in their Huggingface page or Google Drive site. I will maintain a BaiduDisk Link to store these weights for convenience. The link will be realeased when all files are prepared well. 

## Commands
`
- robot-talking
conda activate txchatrob3
cd home/digxxx/robot-talking
sh inference_videoretalking.sh
`

- diff2lip (视频+音频合成)
conda activate diff2lip
cd home/digxxx/diff2lip-main
sh scripts/inference_single_video.sh

- hallo (图片+音频合成)
conda activate jdhallo
cd home/digxxx/hallo-main
python inference.py

- Joyhallo (hallo JD数据集微调版本)
conda activate jdhallo
cd home/digxxx/JoyHallo-main
sh joyhallo-infer.sh

- SyncTalk
conda activate synctalk
cd home/digxxx/synctalk
python main.py data/May --workspace model/trial_may -O --test --asr_model ave --portrait

- Musetalk
conda activate musetalk
cd home/digxxx/MuseTalk-main
python -m scripts.inference --inference_config configs/inference/test.yaml 

## 相关权重文件放在百度网盘中，如有需要，对应下载
https://pan.baidu.com/s/1NZUnVDyE8gTC8ahM0y1oHw?pwd=9qp6 提取码: 9qp6 

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=MuSouth/Digital-Human&type=Date)](https://star-history.com/#MuSouth/Digital-Human&Date)
