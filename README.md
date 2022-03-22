# SKR 1.4 Turbo Installation Guide on Chiron 3D Printer

Marlin Ver 2.0.9.3

[Eng]

Existing Chiron was changed to SKR board due to noise and printing stops, and BL touch, Dwin LCD, and direct extruder were applied.

In addition, the BL touch is unstable symptom and auto-leveling pattern has been corrected.

And we directly modeled and applied direct extruders and motherboard cases.

## Changes 
 
- Change to Direct Extruder

- Change to BL touch instead of Z endstop

- Changed to Dwin LCD (Ender3 V2 LCD) instead of stock LCD

- Change the motherboard (trigorilla board -> SKR 1.4 Turbo)

- change motherboard fan

****

[Kor]

기존의 Chiron은 소음과 인쇄 도중 멈추는 증상 때문에 SKR 보드로 바꾸었으며, BL터치와 Dwin LCD 그리고 다이렉트 익스트루더를 적용했습니다. 

또한 BL터치가 불안정한 증상과 오토 레벨링 패턴을 수정하였습니다. 

그리고 다이렉트 익스트루더 및 메인보드 케이스 등을 직접 모델링 하여 적용하였습니다.

## 변경 사항

- 다이렉트 익스트루더로 변경

- Z endstop 대신 BL터치로 변경

- 재고 LCD 대신 Dwin LCD (엔더3 V2 LCD) 로 변경

- 메인보드 변경 (trigorilla board -> SKR 1.4 Turbo)

- 메인보드 팬 변경

## 필요한 부품 리스트

- **[SD 카드 확장 케이블](https://fr.aliexpress.com/item/4000405842609.html?spm=a2g0o.productlist.0.0.53c846b6Hn52Kr&algo_pvid=180289da-d1b1-4f24-a353-3bc05e539f39&algo_exp_id=180289da-d1b1-4f24-a353-3bc05e539f39-0&pdp_ext_f=%7B%22sku_id%22%3A%2210000001675153781%22%7D&pdp_pi=-1%3B1.79%3B-1%3B-1%40salePrice%3BUSD%3Bsearch-mainSearch)**

- **[Ender 3 V2 LCD](https://ko.aliexpress.com/item/1005002344513406.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140f73gCIA)**

- **[스텝모터 LDO-42STH20-1004ASH](https://ko.aliexpress.com/item/1005003505769393.html?spm=a2g0o.productlist.0.0.17f14283GIIWnm&algo_pvid=73b5fbff-4236-4114-ab6f-0df3ae4475a9&algo_exp_id=73b5fbff-4236-4114-ab6f-0df3ae4475a9-6&pdp_ext_f=%7B%22sku_id%22%3A%2212000026092857083%22%7D&pdp_pi=-1%3B7.32%3B-1%3B-1%40salePrice%3BUSD%3Bsearch-mainSearch)**

- **[XH2.54 커넥터](https://ko.aliexpress.com/item/4000126563819.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140f73gCIA)**

- **[M3 및 M2 볼트/너트 세트](https://ko.aliexpress.com/item/1005002109863123.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140f73gCIA)**

- **[24V Ball 5010 팬 2개](https://ko.aliexpress.com/item/4001073835616.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140f73gCIA)**

- **[BMG 익스트루더](https://ko.aliexpress.com/item/32950787714.html?spm=a2g0o.productlist.0.0.393d2a74uBHDvd&algo_pvid=2e02be82-f3ac-4b90-8d7f-f896545be58d&algo_exp_id=2e02be82-f3ac-4b90-8d7f-f896545be58d-17&pdp_ext_f=%7B%22sku_id%22%3A%2212000025391444054%22%7D&pdp_pi=-1%3B31.33%3B-1%3B-1%40salePrice%3BUSD%3Bsearch-mainSearch)**

- **[SKR 1.4 Turbo With TMC 2209 세트](https://ko.aliexpress.com/item/4000470048293.html?spm=a2g0o.store_pc_allProduct.8148356.11.2e63771cB1wwFl)**

- **[X축 ](https://ko.aliexpress.com/item/33002717446.html?gatewayAdapt=glo2kor&spm=a2g0o.order_list.0.0.21ef140f6FhvkH)**

## 참고 링크

- **[Marlin 펌웨어 설명 블로그](https://m.blog.naver.com/artom212/222001369486)**

- **[Marlin 펌웨어에 대해](https://botop.tistory.com/31)**

- **[Marlin 설정 간략 설명](https://danieryu.tistory.com/16)**

- **[엑셀 및 저크 설명](https://3dprinterly.com/how-to-get-the-perfect-jerk-acceleration-setting/)**

- **[G코드 명령어 설명](https://marlinfw.org/docs/gcode/G000-G001.html)**

- **[오토레벨링 그리드 설정 설명](https://3dprinting.stackexchange.com/questions/8153/how-to-set-z-probe-boundary-limits-in-firmware-when-using-automatic-bed-leveling)**

- **[SKR 보드 설정 platformio.ini 파일](https://www.makenprint.uk/3d-printing/3d-printing-guides/skr-v1-4-marlin-2-setup-part-1/)**

- **[SKR 보드 설정 Configuration.h 파일](https://www.makenprint.uk/3d-printing/3d-printing-guides/skr-v1-4-configuration-h-marlin-2-setup-part-2/)**

- **[SKR 보드 설정 Configuration.adv 파일](https://www.makenprint.uk/3d-printing/3d-printing-guides/skr-v1-4-configuration-adv-marlin-2-setup-part-3/)**

- **[관련 유투브 링크 1](https://www.youtube.com/watch?v=eWGk2dlgvps&t=126s&ab_channel=Jeff%27s3dCorner)**

- **[관련 유투브 링크 2](https://www.youtube.com/watch?v=ZGLryxAw7G4&t=845s&ab_channel=Jeff%27s3dCorner)**

- **[관련 유투브 링크 3](https://www.youtube.com/watch?v=5Tv-4q0UEOs&ab_channel=PatClevenger)**

- **[관련 유투브 링크 4](https://www.youtube.com/watch?v=gzrw0lABCBE&ab_channel=SolutionHungaryOne)**

- **[SKR v1.4 / v1.4 Turbo with TMC2209 Sensorless drivers and Display TFT35 V3.0 가이드](https://3dwork.io/en/complete-guide-skr-v1-4-and-tmc2209/)**

- **[Mini 12864 LCD SKR Board 적용법](https://wiki.fysetc.com/Manual_for_Mini_panel_on_SKR/)**

- **[Mini12864 LCD 배선 및 정보](https://wiki.fysetc.com/Mini12864_Panel/)**

- **[Marlin 2.0.1 펌웨어 올리기(SKR V1.4)](https://m.blog.naver.com/ktdong61/221764619147)**

- **[LCD 펌웨어 업데이트 (LCD에 문제가 있을경우)](https://crosslink.io/2021/02/02/ender-3-v2-how-to-upgrade-firmware-mainboard-and-screen/)**

- **[Fysetc 12864 Panel mount for 2020 프로파일용](https://www.thingiverse.com/thing:3919667)**

- **[Y축 텐셔너](https://www.thingiverse.com/thing:4326955)**

- **[Z축 보강 파츠](https://www.thingiverse.com/thing:4858463)**

- **[벨트 클립](https://www.thingiverse.com/thing:2814851/comments)**

- **[G코드 압축 플러그인(직선운동 -> 곡선운동) 소개](https://blog.naver.com/dukuby/222232870338)**
