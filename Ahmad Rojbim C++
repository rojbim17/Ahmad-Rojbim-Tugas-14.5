#include <stdio.h>

int main()
{
    int A[12] = {60, 80, 55, 90, 75, 40, 50, 85, 70, 65, 45, 55};
    int B[12] = {0};
    int C[12] = {0};
    int i, jB = 0, jC = 0;
    int total = 0;
    float rata;

    // Hitung total
    for (i = 0; i < 12; i++)
    {
        total += A[i];
    }

    // Hitung rata-rata
    rata = total / 12.0;

    // Pisahkan nilai ke B dan C
    for (i = 0; i < 12; i++)
    {
        if (A[i] > rata)
        {
            B[jB] = A[i];
            jB++;
        }
        else if (A[i] < rata)
        {
            C[jC] = A[i];
            jC++;
        }
    }

    // Tampilkan Array A
    printf("Isi Array A : ");
    for (i = 0; i < 12; i++)
    {
        printf("%3d", A[i]);
    }

    // Tampilkan rata-rata
    printf("\nRata-rata Nilai : %.2f", rata);

    // Tampilkan Array B
    printf("\nIsi Array B (Di atas rata-rata) : ");
    for (i = 0; i < jB; i++)
    {
        printf("%3d", B[i]);
    }

    // Tampilkan Array C
    printf("\nIsi Array C (Di bawah rata-rata) : ");
    for (i = 0; i < jC; i++)
    {
        printf("%3d", C[i]);
    }

    return 0;
}
