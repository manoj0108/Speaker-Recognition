clc;clear;close;
fs=8000; //sampling frequency
N=512;   //order

[y_female,Fs,bits]=wavread("D:\V sem\DSP audio\female.wav"); // Reading the wave file of women
[y_male,Fs,bits]=wavread("D:\V sem\DSP audio\male.wav"); // Reading the wave file of men

figure(1);
//plotting the wav file
subplot(211);plot(y_female(1,:));
xtitle('Female voice');
xlabel('bits');
ylabel('recorded signal');

subplot(212);plot(y_male(1,:));
xtitle('Male voice');
xlabel('bits');
ylabel('recorded signal');

y_female = wavread("D:\V sem\DSP audio\female.wav")
y_male = wavread("D:\V sem\DSP audio\male.wav") 
l=length(y_female);
len=length(y_male);
n=0:N-1;
y_female = [y_female,zeros(1,(N-l))];
y_male = [y_male,zeros(1,(N-len))];
Y_female = fft(y_female); //finding the DFT of the women signal
Y_male = fft(y_male); // finding the DFT of the men signal


figure(2);
//plotting the dft of the male and female wav file for 512 sequence
subplot(211);plot2d3(n,abs(Y_female));
xtitle('Female voice');
xlabel('frequency');
ylabel('magnitude');
subplot(212);plot2d3(n,abs(Y_male))
xtitle('Male voice');
xlabel('frequency');
ylabel('magnitude');
