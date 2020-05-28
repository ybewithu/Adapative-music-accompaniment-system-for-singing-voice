# Adapative-music-accompaniment-system-for-singing-voice

There are many mobile applications that record human singing as a mean of entertainment. However, singers sing along the music accompaniment may feel uncomfortable since the music accompaniment could run ahead away or legged away behind. Such asynchronies cause the reduction of music expressiveness as singers. Dynamic time warpping has played a role for the following of singing voice which adapt the singing voice passively as no prediction is applied. This proposed project aims to synchronise singing voice with music accompaniment. With singing voice analysed, the student is expected to find a way to predict the singing voice contour according to existing singing voice contours. Such prediction will be able to make music accompaniment played in a slightly different speed and fit the human singing voice more properly. This technique will enable a sensible process of rehearsal by making the music played in a predictable way fitting human voices. The method that plays music accompaniment at slightly different speed while maintaining voice exist. The main challenge of the project is to find a way to predict human voice contour where either a machine learning method or a signal processing method could be developed. The accuracy of resulting pitch contour can be evaluated by comparing the predicted pitch contour with the real pitch
contour.

The supporting documents are mainly the core of the code in this system.
Due to the limit of the maximum file size, the original traning data cannot be includesd in zip. You can visist : https://pan.baidu.com/s/1-HJypuZUsBzlRnEMHzPeYw 
with the passward：ycyz
to obtain the original training data (including 1027 pieces of pure human singing)

The supporting documents  includes the system part (adjusting) and predicting network part (network).
To start the network, you can use "python network/tra.py", and processed data is integrated in this folder.
To start demo of system, you can use "python demo.py". Due to the limit of the maximum file size, only music "star" can be selected in this system, and this is chinese version.
Just click "record" button and sing following accompaniment, and after singing, click "stop" button.
Your recording with accompaniment processed by system will be generated in test(output) folder, and you can notice that accompaniment is changed during recording.

Notice: Since the system is built based on much software and libarary, some of them are included in supporting documents, but due to the limit of the maximum file size, some of them should be installed in your device.
Therefore, if the system or predicting model cannot run successful, please ensure the needed libaries and software are installed or you can contact with YangBoyi by email: yangboyi@bupt.edu.cn.
