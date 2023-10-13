# SwiftTabBarKullanimi
Swift ve UIKit kullanarak bir tab bar (sekme çubuğu) oluşturmanın temel adımlarını;

Xcode Projesi Oluşturma:
İlk adım olarak Xcode'u açılarak yeni bir proje oluşturulması ardından başlanır.
Tab Bar Controller Eklemek:
Tab bar kullanmak istiyorsanız, projenize bir UITabBarController eklemeniz gerekecek. Bu, sekme çubuğunu yönetmek ve içerik görünümlerini değiştirmek için 
kullanacağınız bir denetleyicidir.
Storyboard'u açın ve başlangıç görünümünüzü veya mevcut bir görünümü seçin.
Sağ taraftaki nesne kitaplığında, "Tab Bar Controller" öğesini arayın ve ana görünümünüze sürükleyin.
Görünümleri Eklemek:
Tab bar ile kullanmak istediğiniz görünümleri eklemelisiniz. Bu görünümler, kullanıcılar sekme çubuğu üzerinden geçiş yapabileceği farklı içerikleri temsil 
eder.
Görünümleri oluşturun veya mevcut olanları kullanın. Örnek olarak, birkaç farklı görünüm (View Controller) oluşturabilirsiniz.
Her bir görünümü tab bar denetleyicisine eklemek için aşağıdaki adımları izleyin:
Tab bar denetleyicinizin üzerini seçin.
Üst tarafta "Editor" menüsünden "Embed in" seçeneğini seçin ve görünümü bağlamak istediğiniz sekmeyi seçin.
Sekme Özelliklerini Ayarlamak:
Her bir sekmenin adını, simgesini ve diğer özelliklerini özelleştirebilirsiniz.
Tab bar denetleyicinizin özelliklerini düzenlemek için Storyboard'da ilgili sekme öğesini seçin ve Sağdaki Özellikler İnpektörünü kullanarak ayarlamalar 
yapın.
İlk Görünümü Belirlemek:
Genellikle, uygulamanızı başlattığınızda hangi sekmenin görünmesini istediğinizi belirlemelisiniz. Bu, tab bar denetleyicinizin "Selected View Controller" 
özelliğiyle yapılır.
Geçişler ve Etkileşimler:
Kullanıcılar farklı sekmelere tıkladığında görünüm değişiklikleri yapmak için geçişleri ve etkileşimleri ele almalısınız. Bu, görünümler arasında geçiş 
yapmak için programlama gerektirebilir.
Uygulamayı Test Etme:
Projeyi simülatörde veya bir gerçek cihazda çalıştırarak sekme çubuğunun nasıl davrandığını test edin.
Swift ve UIKit kullanarak tab bar eklemek oldukça yaygın bir uygulama yapma görevidir. Uygulamanızın gereksinimlerine ve tasarımına bağlı olarak, tab barı
daha karmaşık şekilde özelleştirebilirsiniz. Ayrıca, her bir sekme için ilgili görünüm denetleyicilerini özelleştirmeniz gerekebilir. Bu adımlar, temel bir
tab bar uygulaması oluşturmanıza yardımcı olacaktır.
