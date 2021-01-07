#source 'https://github.com/CocoaPods/Specs.git'
source 'https://mirrors.tuna.tsinghua.edu.cn/git/CocoaPods/Specs.git'

# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

target 'PicApp' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # 网络请求
  # JSON数据(解析数据、生成数据)
  pod 'SwiftyJSON','5.0.0'
  # 图片加载、缓存
  pod 'Kingfisher'

  pod 'Alamofire','=4.8.2'
  
  pod 'YHDragCard.swift'
  
  pod 'HandyJSON','5.0.0'

  pod 'SnapKit','=4.2.0'

end


post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '11.0'
        end
    end
end
