
검수를 너무 대충해서 중복문이나 어색한 부분이 넘쳐나는 상태인 번역문 텍스트 파일입니다.

번역에 도움을 주고싶다면 포크를 만들어서 Text_KinkyDungeon_KR.txt 를 수정하신 후 이곳에 풀 를 요청하시면 됩니다.

요청하시면 검수한 뒤 문제가 없다면 병합한 후 주기적으로 게임에 반영합니다.

단, 인게임의 모든 텍스트가 들어있으므로 스포를 당하실 가능성이 있습니다.

-

Q. 어떻게 수정하나요?

A.번역이 어색한 부분을 수정하시고 중복문을 없애주시면 됩니다.

  게임에 적용되는 방식은 적혀있는 영어 텍스트를 아랫줄에 있는 한국어로 치환하는 방식입니다.
  
  영어 부분은 수정하시면 안됩니다.
  
-

Q.중복문이 뭔가요?

A.예를 들어서


  inventory
  인벤토리


  이런 번역문이 있는데 아래로 내려보니 완전히 똑같은게 또 있을 경우 아래쪽에 있는건 지우시면 됩니다.

-

중복문이 있는 이유는 원본 파일에서 정규식으로 텍스트 키값을 제외한 텍스트를 전부 뽑아서 통째로 번역했는데

원본 파일에선 텍스트 키값이 다르지만 텍스트 자체는 같은 부분들이 중복문이 되는 것입니다.

수정하시기 전에 수정할 부분과 같은 중복문이 있을 경우 수정해도 다른 중복문으로 출력되어 적용이 안되는 것처럼 보일 수 있으니

중복문을 먼저 제거하신 이후에 수정을 하는것이 좋습니다. inventory 같은 짧은 단어일수록 중복문이 많습니다.

-

원본 프로젝트는 https://github.com/Ada18980/KinkiestDungeon 이곳이며,
텍스트 파일의 위치는 KinkiestDungeon/Screens/MiniGame/KinkyDungeon/Text_KinkyDungeon_KR.txt 입니다.
