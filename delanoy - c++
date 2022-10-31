// CPP Program of finding nth Delannoy Number.
#include <bits/stdc++.h>
using namespace std;

// Return the nth Delannoy Number.
int Delannoy(int n, int m)
{
	// Base case
	if (m == 0 || n == 0)
		return 1;

	// Recursive step.
	return Delannoy(m - 1, n) +
		Delannoy(m - 1, n - 1) +
		Delannoy(m, n - 1);
}

// Driven Program
int main()
{
	int n = 3, m = 4;
	cout << Delannoy(n, m) << endl;
	return 0;
}
