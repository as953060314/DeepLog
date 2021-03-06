# DeepLog
A Pytorch implementation of [DeepLog](https://www.cs.utah.edu/~lifeifei/papers/deeplog.pdf)'s log key anomaly detection model.

*If you are confusing about how to extract log key (i.e. log template), I recommend using **Drain** which is proposed in this [paper](https://pinjiahe.github.io/papers/ICWS17.pdf). As far as I know, it is the most effective log parsing method.*

## Requirement
* python>=3.6
* pytorch==1.3.1
* tensorboard==2.0.2

## Dataset
The dataset can be downloaded [HERE](https://www.cs.utah.edu/~mind/papers/deeplog_misc.html).

The prefix of the website for hdfs logs is changed to http://people.iiis.tsinghua.edu.cn/~weixu/, you can download the original data from [raw log](http://people.iiis.tsinghua.edu.cn/~weixu/demobuild.zip) and [200nodes](http://people.iiis.tsinghua.edu.cn/~weixu/200nodes.rar).

## Visualization
Run the following code in terminal, then navigate to https://localhost:6006.

`tensorboard --logdir=log`

## Reference
Min Du, Feifei Li, Guineng Zheng, Vivek Srikumar. "Deeplog: Anomaly detection and diagnosis from system logs through deep learning." ACM SIGSAC Conference on Computer and Communications Security(CCS), 2017.

## Contributing
**If you have any questions, please open an** ***[issue](https://github.com/wuyifan18/DeepLog/issues).***

**Welcome to** ***[pull requests](https://github.com/wuyifan18/DeepLog/pulls)*** **to implement the rest of this paper!**
