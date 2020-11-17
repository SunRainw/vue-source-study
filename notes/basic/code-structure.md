# vue源码的构建
## vue的package.json
<strong style="color:skyblue">main:</strong> npm包的入口，import的时候会通过main去查找入口

<strong style="color:skyblue">module:</strong> webpack2.0以上将module作为默认入口

<strong style="color:skyblue">script:</strong> 定义了很多脚本，每个脚本都是一个任务，源码在src目录下，通过构建生成的代码在dist下

### 构建过程
build通过nodejs执行node scripts/build.js

