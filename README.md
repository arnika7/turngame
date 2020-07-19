# Tetris
JavaSwing을 이용한 테트리스 게임 구현
소켓 통신을 사용하여 2인 play 가능
현재 내 블럭의 위치 값을 String으로 변환하여 매턴마다 소켓 통신을 통해 상대 플레이어 에게 보내어 자신의 화면과 상대의 화면을 모두 확인하며 플레이 가능
블럭 이동(회전)시 이동될 지점의 타일 색을 이용하여 하얀색(바탕색)일 경우에만 이동(회전) 가능하게 구현
time 변수를 통해 스레드 슬립을 time 시간 만큼 걸어주고 매 턴마다 time 값을 점점 작게 하여 점점 빨라지는 테트리스 구현
