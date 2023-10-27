# Lesson.The-matrix
#include <iostream>
#include <stdlib.h>
#include <time.h>
using namespace std;

int main() {
	int mas2d[3][4];

	srand(time(NULL));

	cout << "This is called the matrix: \n";

	for (int j = 0; j < 3; j++)
		for (int i = 0; i < 4; i++)
			 mas2d[j][i] = rand()%10;

	for (int j = 0; j < 3; j++) {

		for (int i = 0; i < 4; i++)
			cout << mas2d[j][i] << " ";
	        cout << endl;
	}

	return 0;
}
