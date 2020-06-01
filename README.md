

	/*연산자
	- 산술연산
	- 관계연산(비교연산)
	- 논리연산
	- 비트연산(2진수)
	
	산술연산의 결과는 값(정수or실수)
	int n=10;
	double if = 12.34;
	char ch ='a';    (아스키 코드로 a=97)

	printf("%d \n", n+20);
	printf("%lf \n", lf+20);
	printf("%d \n", ch+20);
	printf("%d \n",97+20);
	*** char 도 실제로는 정수이다

	printf("%d \n", n*20);
	printf("%lf \n", lf*20);
	printf("%d \n", ch*20);
	printf("%d \n",97*20);

	printf("%d \n", 97/0);
	printf("%lf \n", (double)97/20);
	형변환하기 97이란 정수를 실수로 바꾼 후에 계산을 한다

	형변환 주의사항
	int a = 256;
	double b = a; 정수를 실수로 바뀐다는 뜻
	return 0;

	printf("%d \n", n%5);
	나머지 연산의 결과가 5미만으로 나옴
	*/

	/*관계연산자
	printf("%d \n", 10<2); 0 (거짓)
	printf("%d \n", 10>2); 1 (참)
	결과를 의역하자!!
	*/


	/*논리연산자 (여러 개의 조건식이 조합되었을 때, 식들 간의 순서, 관계를 파악하기)
	printf("%d \n", (1<0) && ('a'==97)); and 연산
	printf("%d \n", (1<0) || ('a'==97)); or 연산
	printf("%d \n", (1<0) !1); 역논리; not 연산 (0이 아닌 모든 수는 거짓(0), 0이면 참(1))
	printf("%d \n", NULL); 거짓(0)
	printf("%d \n", EOF); 참(1) / end of file







	*/
