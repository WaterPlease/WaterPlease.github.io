<h1 style="text-align: center; font-size:xx-large">???</h1>

## About Me

|  이름  |  주소  | 생년월일 |
| :------: | :------: | :------: |
| 권혁진 | 경기도 성남시 | 1996.07.12 |
| 연락처 | 이메일 |   학력   |
| 010-4779-6077 | kwonhuckjin94@gmail.com | 서울대학교 컴퓨터 공학부 |

## Skills

- Langs
  - C
  - C++
  - python
- Stack
  - OpenGL

## Project

####     1. OpenGL toy project

![opengl](./img/OPENGL_TOY_PROJECT/opengl.webp)

**Keyword** : deffered rendering, shadow map, screen space reflection, PBR, tessellation

Git repository : [WaterPlease/OpenGL_TOY_PRJ (github.com)](https://github.com/WaterPlease/OpenGL_TOY_PRJ)

<details>
    <summary>접기/펼치기</summary>
    <p>
        그래픽스 강의를 수강한 이후 관련 분야에 흥미가 생겨 더 공부해볼 목적으로 진행한 토이 프로젝트입니다. 흥미로운 기술들을 발견하면 공부하고 그것을 해당 프로젝트에 적용 시켜왔습니다.<br/>
이후에도 지속적으로 공부하면서 다양한 기능을 추가할 예정입니다.
    </p>
    <p>
Feature <br/>
&nbsp;&nbsp;&nbsp;&nbsp;- Deffered rendering<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- Screen space reflection<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- Shadow mapping<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- jittered PCF with 64 samples at most.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- Tone mapping, gamma correction<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- Bloom effect<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- PBR<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- Normal mapping<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- tessellation<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- LOD<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- view cone culling<br/>
    </p>
</details>


####     2. 레이트레이싱

<img src="./img/RAYTRACER/mirror_raytrace.png" alt="mirro" style="zoom: 75%;" />

**Keyword** : BVH, 레이트레이싱, 멀티코어

Git repository :  [WaterPlease/RAYTRACING (github.com)](https://github.com/WaterPlease/RAYTRACING)

Detailed documentation : https://github.com/WaterPlease/RAYTRACING/raw/main/HW5.pdf

<details>
    <summary>설명</summary>
<p>
그래픽스 강의 마지막 과제 결과물입니다. 한 학기 동안 배운 여러 내용과 과제 결과물을 기반으로 레이트레이서를 작성하였습니다. 때문에 한 학기 동안 그래픽스 강의를 들으며 학습한 여러 내용들을 재차 확인할 수 있었습니다. 또한 최적화를 위해 조사해보며 KD tree, Octree, bsp와 같은 공간분할 방법들을 익혀볼 수 있었습니다.
</p>
<p>
Feature<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- BVH for acceleration<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- backward ray tracing<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- reflection<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- refraction<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- shadow<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- distributed raytracing<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- multisampling<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- soft shadow<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- rough mirror<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- .obj file import<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- scene import & viewer<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- swept surface<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- spline curve and bezier curve<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- phong illumination<br/>
&nbsp;&nbsp;&nbsp;&nbsp;- multicore support<br/>
</p>
</details>

#### 3. Matrix multiplication accelerator on FPGA

![hdc](./img/HDC/hdc.png)

Git repository : [sdasd-asdsad/prj_v0 (github.com)](https://github.com/sdasd-asdsad/prj_v0#mlp1)

keyword : verilog, MLP, matrix multiplication

담당한 부분

1. 대부분의 하드웨어 코드 작성
   - 두 floating point 값의 곱을 제외한 모든 코드 작성
2. transforming convolution into matrix multiplication
3. support hardware acceleration for matrix multiplication

####     4. CK3 DNA Editor on web

![](./img/CK3_DNA_EDITOR/ckdna1.png)

![](./img/CK3_DNA_EDITOR/ckdna2.png)

link : https://sdasd-asdsad.github.io/CK3DNA_Edit/

- Keyword : base64

<details>
    <summary>접기/펼치기</summary>
??인 크루세이더 킹즈3의 캐릭터 외형 수정을 위한 DNA 에디터 입니다.
</details>

