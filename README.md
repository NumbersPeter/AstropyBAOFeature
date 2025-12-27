# AstropyBAOFeature
2-POINT CORRELATION FUNCTION을 사용해 계산한 은하 분포 데이터를 활용한 BARYON ACOUSTIC OSCILLATOIN을 통한 우주 초기 물리량 계산

# AstropyBAOFeature

## 프로젝트 목표
학부 논문 기반 BAO feature 재현 + Python/GitHub 역량 향상

## 데이터
SDSS DR12 CMASS Galaxies + Random Catalog

## 분석 파이프라인
1. Data load
2. Comoving coordinate transform
3. Pair counts (DD, DR, RR)
4. 2PCF using Landy–Szalay
5. BAO feature visualization



## 📌 설치 및 실행
```bash
pip install -r requirements.txt
python src/main.py
