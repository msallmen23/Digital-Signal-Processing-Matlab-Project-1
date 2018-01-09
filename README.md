# Digital-Signal-Processing-Matlab-Project-1
# Written by Michael Jordan Sallmen and William Thomas Sprinkle
# You can try and compiling the following in MATLAB or you may open the word document that is attached

% Problem #1: given the two signals x1(t)=cos(20*pi*t) and x2(t)=cos(100*pi*t)
% Sample these two signals with a) Fs=40Hz and b) Fs=100Hz
%Problem #1 MATLAB Solution:
% part a) when Fs=40Hz the following MATLAB code will plot x1(n) and x2(n)

clear
clc
Fs1=40;
i=1;
for n=0:1:60
t1 = n/Fs1;
t2 = n/Fs1;
t11(i) = t1;
t22(i) = t2;
x1 = cosd(20*pi*t1);
x11(i) = x1;
x2 = cosd(100*pi*t2);
x22(i) = x2;
i=i+1;
end
figure
subplot(2,1,1)
stem(x11)
title('x1(n) = cos(0.5\pin)')
xlabel('n')
ylabel('x1')
subplot(2,1,2)
stem(x22)
title('x1(n) = cos(0.2\pin)')
xlabel('n')
ylabel('x2')


% part b) when Fs=100Hz the following MATLAB code will plot x1(n) and x2(n)
clear
clc
Fs2=100;
i=1;
for n=0:1:60
t1 = n/Fs2;
t2 = n/Fs2;
t11(i) = t1;
t22(i) = t2;
x1 = cosd(20*pi*t1);
x11(i) = x1;
x2 = cosd(100*pi*t2);
x22(i) = x2;
i=i+1;
end
figure
subplot(2,1,1)
stem(x11)
title('x1(n) = cos(0.2\pin)')
xlabel('n')
ylabel('x1')
subplot(2,1,2)
stem(x22)
title('x1(n) = cos(\pin)')
xlabel('n')
ylabel('x2')


 

