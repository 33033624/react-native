# react-native 总结的插件
``
 1 react-native-contacts 获取手机联系人的插件
 提供两个地址  （1）官方的地址https://github.com/rt2zz/react-native-contacts   
 
              (2)经过改造的可以获取到Android手机的短信和通话记录https://github.com/bluefiresky/react-native-contacts.git      
              
              按照（1）的官方文档配置后，需要在app/android/app/src/main/AndroidManifest.xml添加    
                 
                 
              <uses-permission android:name="android.permission.READ_SMS"/>   
                   
                   
              <uses-permission android:name="android.permission.READ_CALL_LOG"/>
``
