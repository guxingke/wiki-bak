并发 **SNAPSHOT**
<!-- more -->

## 线程
线程与锁模型其实是对底层硬件运行过程的形式化. 这种形式化既是该模型最大的优点, 也是它最大的缺点. 

### 新建线程
- 继承 Thread 类
- 实现 Runnable 接口
-  实现 Callable 接口

### Java 线程状态机
![thread](_images/state-machine-example-java-6-thread-states.png)

### 线程基本操作
- sleep
- join
- yield
- interrupt

### 守护进程
> A program terminates all its activity and exits when one of two things happens:     
> - All the threads that are not daemon threads terminate.  
> - Some thread invokes the exit method of class Runtime or class System, and the exit operation is not forbidden by the security manager.

### ThreadLocal


## Synchronized
synchronized Java 并发关键字之一. 
### 基本使用
### 基本原理
### 锁优化
### 锁升级

## Java 并发工具包,  J.U.C 
Java 并发工具包,  JSR166. 

### ReentrantLock

### AQS

### 线程池

### 并发容器


## Java 内存模型, JMM

