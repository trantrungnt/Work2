# Work2
Learn AsyncTask

##Yêu cầu
+ Viết chương trình download file sử dụng Async Task

##Kiến thức về Async Task
+ Có thể hiểu Async Task là 1 thread độc lập và được Google Android phát triển, sau đó lập trình viên kế thừa thread này và phát triển: xử lý các tác vụ nặng. 
+ Để Async Task tương tác được với giao diện và với main thread, ta sử dụng các phương thức đã được tạo sẵn và Override theo bài toán của mình mong muốn (onPreExecute() , doInBackground(), onPostExecute(), onProgressUpdate()). Trong đó, doInBackGround() để xử lý các công việc nặng kiểu như tải file ... onPreExecute() để khởi tạo giao diện và thanh trạng thái, onProgressUpdate() để cập nhật giá trị của thanh progress bar và cập nhật lên thanh progress bar thông qua publishProgress() -> giá trị này lấy từ doInBackGround()
![Bài giảng Async Task - by CanhBX](http://i477.photobucket.com/albums/rr132/trungepu/asyn-task-by-canhbx_zpsuszfgpgp.jpg)

##Tham khảo
+ [Android Async Task](http://programmerguru.com/android-tutorial/android-asynctask-example/)
