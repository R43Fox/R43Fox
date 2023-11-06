- 👋 Hi, I’m @R43Fox
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
p += 0.5*sin( t*vec2(1.1,1.3)+vec2(0.0,0.5) );

float a = atan( p.y, p.x );
float r = length( p );

float s = r * (1.0+0.5*cos(t*1.7));

vec2 uv = 0.1*t + 0.05*p.yx + 0.05*vec2( cos(t+a*2.0),  
                                         sin(t+a*2.0))/s;

return texture( iChannel0, 0.5*uv ).xyz;}
<!---
R43Fox/R43Fox is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
