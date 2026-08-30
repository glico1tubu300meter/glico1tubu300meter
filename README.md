### 🙋 About me

- 🖥️ 普段はローカルGPU環境でLLM・VLM(Vision-Language Model)まわりを触っています
- 🎓 機械学習・データ分析まわりのバックグラウンドで、いまは画像認識・LLM/VLM分野を中心に開発しています
- 🔭 ロボット制御シミュレーションからLLMのファインチューニングまで、手を動かして学ぶのが好きです
- 🤖 調査・実装には **[Claude](https://www.anthropic.com/claude) / Claude Code** をフル活用しています
- 🎮 息抜きはゲーム。特にソウルライク系とオープンワールド系が好きで、探索して発見する体験や歯応えのあるボス戦にハマってます

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white" alt="CUDA">
<img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" alt="Ollama">
<img src="https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white" alt="Claude">
</p>

---

### 🚀 Projects

**🌊 [flow-matching-sample](https://github.com/glico1tubu300meter/flow-matching-sample)**

Flow Matching / Rectified Flowの実装・実験集。2Dトイデータ→MNIST→CIFAR-10と段階的に発展させ、Classifier-Free Guidance・U-Net/DiT・VAE潜在空間・Reflowなどを実験しています。
`Flow Matching` `PyTorch` `DiT` `VAE`

**🤖 [vision_language_model](https://github.com/glico1tubu300meter/vision_language_model)**

物理シミュレータ **Genesis** とローカルVLM(Ollama/LLaVA)を組み合わせた、マルチエージェント方式のロボット制御シミュレーション。視覚情報をもとにロボットが赤いキューブのピック&リフト動作を自律実行します。
`Genesis` `Ollama/LLaVA` `Inverse Kinematics` `Python`

**🧠 [lora-basic-toolkit](https://github.com/glico1tubu300meter/lora-basic-toolkit)**

QLoRA(4bit量子化 + LoRA)によるローカルLLMファインチューニングの最小構成ツールキット。Qwen2.5-7B-Instructなどをベースに、学習・推論・アダプタ比較までを一通り実行できます。
`QLoRA` `Hugging Face` `NVIDIA CUDA` `Python`

**👁️ [vlm-basic-toolkit](https://github.com/glico1tubu300meter/vlm-basic-toolkit)**

Vision-Language Model(Qwen2.5-VL-7B-Instruct、4bit量子化)を最小構成で動かすツールキット。画像キャプション生成・自由形式の質問応答(VQA)・物体検出(バウンディングボックス描画)に対応しています。
`Qwen2.5-VL` `Transformers` `CUDA` `Python`

**🎥 [comfyui-i2v-tools](https://github.com/glico1tubu300meter/comfyui-i2v-tools)**

ComfyUI + LTX-Video / Stable Video Diffusion(SVD-XT)による画像条件付き動画生成の補助スクリプト集。被写体を保護したままのマスクimg2img、複数画像をフレーム位置に紐づけて誘導する長尺のマルチキーフレーム生成に対応しています。
`ComfyUI` `LTX-Video` `Stable Video Diffusion` `Python`

**🔍 [rag-basic-toolkit](https://github.com/glico1tubu300meter/rag-basic-toolkit)**

RAG(検索拡張生成)の最小構成実装ツールキット。JSONLコーパスから埋め込みベクトルを生成しFAISSでインデックス化、質問に対して関連文書を検索してLLMが回答を生成します。コーパスに無い情報は無理に答えない設計です。
`FAISS` `multilingual-e5-large` `Qwen2.5-7B` `Python`

**🎬 [claude-slides](https://github.com/glico1tubu300meter/claude-slides)**

Claude Codeで作成したHTMLスライド(reveal.jsベース)の公開アーカイブ。外部CDNに依存しない単一HTMLファイルとして、オフラインでも閲覧可能。ライト/ダークテーマ自動切り替え対応。
`reveal.js` `HTML` `GitHub Pages`

**📝 [claude-aws-quiz-skill](https://github.com/glico1tubu300meter/claude-aws-quiz-skill)**

AWS認定試験対策の2択クイズを生成するClaude Codeカスタムスキル。試験区分・難易度・トピックを指定するだけでHTML形式のクイズを作成し、`localStorage`で自動保存・再開、出題重複も自動で回避します。
`Claude Code Skill` `HTML` `JavaScript`
