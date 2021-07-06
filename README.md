# twitter020
#つぶやきProcessing void setup(){size(500,500);}float k,i,w=500,h=w/2;void draw(){background(64);fill(0);noStroke();triangle(0,w,h,h,w,w);fill(32);triangle(375,w,h,h,w,w);for(i=0;i&lt;TAU;i+=0.002){stroke(0,h,h,map(noise(k),0,1,32,64));line(h,h,w*cos(i+k)+h,w*sin(i+k)+h);}k+=2;}
