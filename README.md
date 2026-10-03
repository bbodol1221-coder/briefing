# 아침 브리핑 보드 (공개판)

보유 종목과 뉴스 요약을 보여 주는 정적 페이지입니다. 데이터는 Supabase의 `public_dashboard()` 함수로만 읽고, 수정은 관리자 로그인 후 `admin_upsert_holding()`으로만 가능합니다.
