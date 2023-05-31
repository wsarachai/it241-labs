# it214-labs
## Lab 01
### 1. ให้นักศึกษาติดตั้งโปรแกรม Git โดยสามารถดูวิธีติดตั้งได้ตามลิงค์นี้ [การติดตั้งโปรแกรม Git (Git Installation)](https://itsci.mju.ac.th/~watcharin/wordpress/?p=1)
### 2. ให้นักศึกษาติดตั้งโปรแกรม Docker Desktop โดยสามารถดูวิธีติดตั้งได้ตามลิงค์นี้ [ติดตั้ง Docker Engine (Install Docker Engine)](https://itsci.mju.ac.th/~watcharin/wordpress/?p=90)
### 3. เริ่มการทำงาน Docker (Start Docker Desktop)
### 4. Create the container
#### 4.1 สำหรับระบบปฏิบัติการ MaxOS, Linux ให้ใช้คำสั่งนี้
    docker run --name ubuntu-itsci -it --rm wsarachai/ubuntu-itsci:latest
#### 4.2 สำหรับระบบปฏิบัติการ Window ให้ใช้คำสั่งนี้
    docker run --name ubuntu-itsci -it --rm wsarachai/ubuntu-itsci:linux-amd64

## Lab 02

## Run the container
    ```
    docker run --name itsci-mysql -v C:\mysql-data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=1234 -d --rm -p 3306:3306 wsarachai/mysql-itsci:latest
    ```


