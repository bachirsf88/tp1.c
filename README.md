#include <stdio.h>

int main() {
    int i,j;
    char D[5][5] = {
        {'1', '2', '3', '4', '5'},
        {'7', 'a', 'c', '8', 'd'},
        {'c', '9', '4', 'z', '8'},
        {'5', '6', 'p', 'n', '3'},
        {'2', '9', 't', 'm', 'k'}        
    };
سؤال الاول//
    for ( i = 0; i < 5; i++) {
        for ( j = 0; j < 5; j++) {
            printf("%c ", matrix[i][j]);
            printf("\n");
        }
    }
//سؤال الثاني

    return 0;
}
