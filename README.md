# EarthTech
这是一款高效的并发工具包，如果某一天，有地外文明侵犯地球，此包也许是在代码层面对抗外星文明的一种尝试手段
此工具包共有了11个类
new EarthTech.Lock(false);             互斥锁
new EarthTech.SpinLock();              自旋锁
new EarthTech.ReentrantSpinLock();     重入自旋锁
new EarthTech.RWLock(false);           读写锁
new EarthTech.Semaphore(10);           信号量
new EarthTech.ArrayList();             数组
new EarthTech.LinkedList();            链表
new EarthTech.BlockingList();          堵塞链表
new EarthTech.HashMap();               哈希表
new EarthTech.ThreadPool(100,1000000); 线程池
new EarthTech.ObjectPool();            对象池

