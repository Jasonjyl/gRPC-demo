# gRPC-demo

本项目为简单demo，主要用于了解、学习gRPC的基本概念和使用

## 1. 安装gRPC
```
go get -u google.golang.org/grpc
```

## 2. 安装Protocol Buffers v3
下载地址：https://github.com/google/protobuf/releases

### 2.1 解压

### 2.2 把protoc二进制文件的路径加到环境变量

## 3. 安装protoc的Go插件
```
go get -u github.com/golang/protobuf/protoc-gen-go
```

## gRPC四种服务类型

### 1. 简单rpc

简单来讲就是，在不考虑异常的情况下，客户端发送一个请求，服务器返回一个响应

### 2. 服务端流式rpc
客户端发送一个请求，服务端以流的形式返回响应

### 3. 客户端流式rpc
客户端以流的形式发送请求，服务端返回一个响应

### 4. 双向流式rpc
客户端和服务端均以流的形式进行通信
