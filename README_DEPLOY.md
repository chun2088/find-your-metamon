# 배포 방법

이 페이지는 정적 사이트라 `index.html`만 업로드해도 동작합니다.

## Netlify Drop

1. 아래 폴더를 압축하거나 폴더째 준비합니다.

   ```text
   C:\Users\User\Documents\Codex\2026-06-06\new-chat
   ```

2. https://app.netlify.com/drop 에 접속합니다.
3. 이 폴더를 드래그해서 올립니다.
4. 생성된 `https://...netlify.app` 주소를 모바일에서 열면 됩니다.

## GitHub Pages

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소 루트에 업로드합니다.
3. 저장소 `Settings` -> `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, 폴더를 `/root`로 선택하고 저장합니다.
6. 잠시 뒤 표시되는 `https://계정명.github.io/저장소명/` 주소로 접속합니다.

## 로컬 확인

PC에서 이 폴더로 이동한 뒤 실행합니다.

```powershell
node serve-local.mjs
```

모바일과 PC가 같은 Wi-Fi에 있으면 아래 주소로 접속합니다.

```text
http://192.168.219.100:8000
```

