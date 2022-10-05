# EarthTech
这是一款高效的并发工具包，如果某一天，有地外文明侵犯地球，此包也许是在代码层面对抗外星文明的一种尝试手段
此工具包共有了11个类
EarthTech.Lock lock = new EarthTech.Lock(false);                      互斥锁 
EarthTech.SpinLock lock = new EarthTech.SpinLock();                   自旋锁 
EarthTech.ReentrantSpinLock lock = new EarthTech.ReentrantSpinLock(); 重入自旋锁 
EarthTech.RWLock rwlock = new EarthTech.RWLock(false);                读写锁 
EarthTech.Semaphore se = new EarthTech.Semaphore(10);                 信号量 
EarthTech.ArrayList list = new EarthTech.ArrayList();                 数组 
EarthTech.LinkedList list = new EarthTech.LinkedList();               链表 
EarthTech.BlockingList list = new EarthTech.BlockingList();           堵塞链表 
EarthTech.HashMap hm = new EarthTech.HashMap();                       哈希表 
EarthTech.ThreadPool tp = new EarthTech.ThreadPool(100,1000000);      线程池 
EarthTech.ObjectPool op = new EarthTech.ObjectPool();                 对象池 

