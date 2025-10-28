# llm_basic_ex
생성형 ai api 활용 실습

# conda 가상환경 마들기
```
# 새로운 가상환경 만들기
conda create -n llm_env python=3.10
conda activate llm_env

#가상환경 활성화
conda activate llm_env

#jupyter lab에 가상환경 연동하기
- jupyter 노트북에서 파이썬 코드를 실행할 수 있는 파이썬 커널
pip install ipykernal

-jupyter lab에 가상환경(llm_env) 등록하기
python -m ipykernal install --user --name llm_env
```

# openai gpt 모델 api 사용방법 실습
## 라이브러리 설치
```
#OPENAI사의 AI모델 라이브러리 설치
pip install openai
```

## 오디오 파일 인식 오류시, chololately 파일 설치
Windows에서 FFmpeg 설치
> Chocolatey 설치
Chocolatey가 설치되어 있지 않다면 다음 단계를 따라 설치할 수 있습니다:

1) 관리자 권한으로 PowerShell을 엽니다.(x86)

2) 다음 명령어를 실행하여 Chocolatey를 설치합니다:<br/>
아래 코드는 다음 링크에서 찾을 수 있음, 꼭 최신 버전을 확인할 것. : https://chocolatey.org/install <br/>
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
    
3) Chocolatey 설치가 완료되면, 다음 명령어로 FFmpeg를 설치할 수 있습니다:
choco install ffmpeg

4) 설치 완료 후 터미널과 code를 모두 종류한 후 재실행 하여 적용한다.

* chocolately 설치 여부를 확인하기 위해서는 powershell에 **choco --v**라고 작성하여 설치된 버전을 확인하다.

# google llm 모델 api 사용 방법
```
pip install google-genai
```
