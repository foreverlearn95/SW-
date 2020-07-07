## SW 최적화 캠프

LP로 시작한 건 주어진 예제 코드이고
exercise, problem이 직접 해본 코드다.
github를 처음 시작할 겸 만들었습니다.

# 준비사항
anaconda prompt를 관리자 모드로 열어 해당 폴더 경로로 이동해서
conda create --name environment이름 python=3.6 으로 환경을 만들고
activate environment이름 으로 환경을 사용한다.
또 pip install numpy pandas jupyterlab cvxpy==1.0.25 로 사용 package 설치한다.
(optional)
pip install cplex 또는 conda install -c ibmdecisionoptimization cplex(권장) 으로 
cplex를 설치하고 cplex.__version__으로 설치가 완료되었는지 체크한다.

Homework1 문제들은 선형대수학적인 지식이 많이 들어가있고
Homework2 문제들은 OS와 알고리즘(Genetic algorithm 포함)문제가 들어가있다.

하지만 이번 짧은 캠프에서 모든 내용을 습득하지 못해 homework1 의 1,2,4,5번 문제만 풀었다.