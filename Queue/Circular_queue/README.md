## 数据类型定义
```cpp
typedef struct {
    PNode *elem;
    int front,rear;
    int queuesize;
}XhQueue;
```
## 初始化
```cpp
void InitQueue(XhQueue &Q,int maxsize){
    Q.elem=new PNode[maxsize];
    if(Q.elem!=NULL){
        Q.front=Q.rear=0;
        Q.queuesize=maxsize;
    }
}
```
## 入队
```cpp
void EnQueue(XhQueue &Q,PNode p){
    if((Q.rear+1)%Q.queuesize!=Q.front){
        Q.elem[Q.rear]=p;
        Q.rear=(Q.rear+1)%Q.queuesize;
    }
}
```
## 出队
```cpp
void DeQueue(XhQueue &Q,PNode &p){
    if(Q.front!=Q.rear){
        p=Q.elem[Q.front];
        Q.front=(Q.front+1)%Q.queuesize;
    }
}
```
## 取队头
```cpp
void GetHead(XhQueue &Q,PNode &p){
    if(Q.front!=Q.rear){
        p=Q.elem[Q.front];
    }
}
```
## 判空
```cpp
int EmQueue(XhQueue Q){
    if(Q.front!=Q.rear)return 0;
    else return 1;
}
```
