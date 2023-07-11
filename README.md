# ChefAndIpcCertificate
# cook your dish here
N,M,K = map(int,input().split())
i = 1
count = 0
while i<=N:
  l = list(map(int,input().split()))
  i+=1
  X = l.pop(-1)
  if sum(l)>=M and X<=10:
    count+=1
print(count)
