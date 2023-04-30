# YOLO-series-Paper-Review
IVPG Lab interns seminar - YOLO Papar Review

## You Only Look Once: Unified, Real-Time Object Detection

<p align="center">
    <img width="100%" src="One and Two.png" style="max-width:100%;"></a>
</p>

- RCNN, SPP, Fast RCNN, Faster RCNN 모델은 Two-Stage 모델입니다. 여기서 Two란, 위의 오른쪽 그림처럼 Region Proposal과 Object Detection 단계를 분리해 전개되는 모델들을 말합니다. 반면에 YOLO와 같은 One-Stage 종류의 모델들은 Region Proposal 과 Object Detection을 따로 분리하지 않고 한 번에 수행하는 모델입니다.

- Two-Stage 모델들의 학습 속도가 느리기 때문에 One-Stage 모델들이 등장하게 되었습니다. Object Detection 분야에서 객체를 얼마나 탐지를 잘 하느냐 도 중요하지만 탐지를 얼마나 '빨리' 하느냐 도 마찬가지로 중요하기 때문입니다.
 
논문에서 나온 것처럼, 컴퓨터가 자동차를 특정한 센서 없이 운전할 수 있으려면, 실시간으로 들어오는 정보를 빠르고 정확하게 분석 할 수 있어야 가능하기 때문에 Object-Detection에서는 검출 속도 또한 정확성과 함께 가져가야 합니다.
 
그런데 Two-Stage 모델들은 탐지 성능은 뛰어나지만 상대적으로 탐지 속도는 매우 느린 편입니다. 따라서 연구자들은 이러한 느린 탐지 속도문제를 해결하고자 One-Stage 모델인 YOLO(You Only Look Once)라는 Real-Time Object Detection을 개발했습니다.

Paper Review -> [Notion](https://flashy-skipjack-375.notion.site/You-Only-Look-Once-Unified-Real-Time-Object-Detection-0c29049703f747ce8f83ddda73171d32)
