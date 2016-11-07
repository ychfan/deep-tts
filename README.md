# deep-tts
Deep Learning based Text-to-Speech Synthesis (under construction)

##To Do List
1. Feature extraction
   1. Linguistic: ourselves (or [Festival](http://festvox.org/festival/index.html) as backup)
   2. Acoustic: [WORLD](https://github.com/mmorise/World)
2. State alignment: 
   1. [Kaldi](https://github.com/kaldi-asr/kaldi) (Refer to [Merlin](https://github.com/CSTR-Edinburgh/merlin): *The frame alignment and state information was obtained from forced alignment using a monophone HMM-based system with 5 emitting states per phone.* Based on my previous experience, obejective model measurements highly depend on a accurate alignment.)
   2. [HTS](http://hts.sp.nitech.ac.jp) as backup
3. Neural network: [MXNet](https://github.com/dmlc/mxnet) (or [CNTK](https://github.com/Microsoft/CNTK) as backup)
