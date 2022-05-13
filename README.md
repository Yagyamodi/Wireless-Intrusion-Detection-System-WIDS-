# Wireless-Intrusion-Detection-System-WIDS-

Our aim was to enhance the security and improve the detection detection ability of malicious intrusion behaviour by a device connected to a wireless network. For that, we have trained a Random forest model on AWID-3 dataset. The AWID-3 dataset includes the features collected by implementing various types of attacks such as Deauthentication attack, Evil Twin attack, Website spoofing attack, SQL Injection attack. 
After training our intrusion detector, we have automated the real-time detection using the tshark and tkinker python libraries. To evaluate the performance of our intrusion detector, we have ran the inference of our detector while simultaneously running the deauthentication and evil twin attacks in real-time. We have also evaluated the performance of the detector on other attacks by running the inference on test dataset.
