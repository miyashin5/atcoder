#D - Lucky PIN  https://atcoder.jp/contests/sumitrust2019/tasks/sumitb2019_d

N = int(input())
S = str(input())

a = list(S)

num = []


for i in range(N-2):
   for j in range(i+1,N-1):
        for k in range(j+1,N):
            temp = 0
            temp = a[i] + a[j] + a[k]
            num.append(temp)

print(len(set(num)))
