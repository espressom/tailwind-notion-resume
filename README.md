# tailwind-notion-resume
A lightweight resume format designed using HTML and Tailwind CSS CDN, developed to address the issues of font distortion and improper scaling when exporting resumes from Notion to PDF.

## Project Structure
```
project-root/
├── assets/
│   └── logo.svg
└── resume.html
```

## CDN Integration

This project includes the following CDNs:

1. **TailwindCSS**: [Official Website](https://tailwindcss.com/) / [GitHub](https://github.com/tailwindlabs/tailwindcss)
   ```html
   <script src="https://cdn.tailwindcss.com"></script>
2. **Pretendard**: [Official Website](https://cactus.tistory.com/306) / [GitHub](https://github.com/orioncactus/pretendard)
   ```html
   <link
      rel="stylesheet"
      as="style"
      crossorigin
      href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css"
   />


## How to Use
1. Open the `resume.html` file and add the necessary content. You can apply TailwindCSS using inline styles in the basic template.
3. Replace the `logo.svg` with the logo of the company you are applying to and adjust the size of the logo appropriately.
   ```html
   <img src="./assets/logo.svg" alt="logo" class="w-{YOUR_LOGO_SIZE} ml-auto" />
5. Open the completed `resume.html` file in a browser, right-click on the page, and open the print dialog.
6. Go to the additional settings and choose a scale that ideally separates the sections of the resume, and adjust the margins if necessary.


# 프로젝트 소개
HTML과 Tailwind CSS CDN을 사용하여 디자인된 경량 이력서 포맷으로, 노션에서 PDF로 이력서를 내보낼 때 발생하는 글꼴 왜곡 및 크기 조정 문제를 해결하기 위해 개발되었습니다.

## 프로젝트 구조
```
project-root/
├── assets/
│   └── logo.svg
└── resume.html
```

## CDN 정보

이 프로젝트는 다음 CDN을 포함하고 있습니다:

1. **TailwindCSS**: [Official Website](https://tailwindcss.com/) / [GitHub](https://github.com/tailwindlabs/tailwindcss)
   ```html
   <script src="https://cdn.tailwindcss.com"></script>
2. **Pretendard**: [Official Website](https://cactus.tistory.com/306) / [GitHub](https://github.com/orioncactus/pretendard)
   ```html
   <link
      rel="stylesheet"
      as="style"
      crossorigin
      href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css"
   />

## 사용 방법
1. `resume.html` 파일을 열고 필요한 내용 추가합니다. 기본 템플릿에서 인라인 스타일로 tailwindcss을 적용할 수 있습니다.
2. `logo.svg`를 지원하는 회사의 로고로 변경하고 로고의 크기를 적절하게 수정합니다.
   ```html
   <img src="./assets/logo.svg" alt="logo" class="w-{로고_크기} ml-auto" />
2. 작성된 `resume.html` 파일을 브라우저에서 열고, 페이지를 우클릭해 인쇄하기 대화상자를 켭니다.
3. 기타 설정에 들어가 이력서의 항목이 이상적으로 구분되는 배율을 선택하고, 필요한 경우 여백을 조절합니다.
   ![image](https://github.com/espressom/tailwind-notion-resume/assets/45090300/c1d06acf-99d8-4a20-86ed-5f7bf6caac14)
