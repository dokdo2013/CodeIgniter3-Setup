# CodeIgniter3-Setup
실제 서버에 바로 배포하여 사용할 수 있도록 커스터마이징된 코드이그나이터3 최종배포판 (ver 3.1.1)

## 사용법
#### 1) .htaccess 파일 수정
5번째 줄 {{주소입력}} 영역 대체
```
http://example.com/$1
```

#### 2) application/config/config.php 파일 수정
26번째 줄 {{주소입력}} 영역 대체
```php
$config['base_url'] = 'http://example.com';
```

## 주요 기능
- 기존 코드이그나이터3의 example 파일들과 불필요한 파일들을 삭제하여 용량을 줄였으며, 기본적으로 index.php 없이 라우팅됩니다.
- Default Controller가 main으로 세팅되어 있어 http://{도메인주소}/main 으로 접속하여 바로 이용 가능합니다.

## 라이센스
코드이그나이터3는 기본적으로 MIT 라이센스입니다.
본 배포버전 역시 동일하게 MIT 라이센스를 따릅니다.