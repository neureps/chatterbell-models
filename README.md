# chatterbell-models

종알(Chatterbell) 앱이 받는 **온디바이스 엔진 자산 배포처**. 파일은 git이 아니라
**릴리스 에셋**으로 올린다(HF CDN이 셀룰러에서 느려 서빙 층을 여기로 둔다).

- 현재 릴리스: [`engine-v1`](../../releases/tag/engine-v1) — CosyVoice3 w4g32f8 stream ONNX (candidate)
- **화자 프로필(보이스 팩)은 여기 없다.** 모델 그래프·임베딩·토크나이저뿐이며 클로닝용
  분석 모델도 포함하지 않는다.
- 원본 보존·레지스트리 정본: HF `neureps/chatterbell-cosyvoice3-onnx`(private)
- 제조법·판정: `ondevice-models/projects/chatterbell/model/MODEL-RELEASE.md` §1
- 라이선스: upstream `FunAudioLLM/Fun-CosyVoice3-0.5B-2512` Apache-2.0 상속 + NOTICE
