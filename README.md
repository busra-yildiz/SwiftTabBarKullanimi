# SwiftTabBarKullanimi

Swift ve UIKit kullanarak bir tab bar (sekme çubuğu) oluşturmanın temel adımlarını;

1. Xcode Projesi Oluşturma:
İlk adım olarak Xcode'u açılarak yeni bir proje oluşturulması ardından başlanır.
2. Tab Bar Controller Eklemek:
Tab bar kullanmak istiyorsanız, projenize bir UITabBarController eklemeniz gerekecek. Bu, sekme çubuğunu yönetmek ve içerik görünümlerini değiştirmek için kullanacağınız bir denetleyicidir.
3. Storyboard'u açın ve başlangıç görünümünüzü veya mevcut bir görünümü seçin.
Sağ taraftaki nesne kitaplığında, "Tab Bar Controller" öğesini arayın ve ana görünümünüze sürükleyin.
4. Görünümleri Eklemek:
Tab bar ile kullanmak istediğiniz görünümleri eklemelisiniz. Bu görünümler, kullanıcılar sekme çubuğu üzerinden geçiş yapabileceği farklı içerikleri temsil eder.Görünümleri oluşturun veya mevcut olanları kullanın. Örnek olarak, birkaç farklı görünüm (View Controller) oluşturabilirsiniz.
Her bir görünümü tab bar denetleyicisine eklemek için aşağıdaki adımları izleyin:
1. Tab bar denetleyicinizin üzerini seçin.
2. Üst tarafta "Editor" menüsünden "Embed in" seçeneğini seçin ve görünümü bağlamak istediğiniz sekmeyi seçin.
Sekme Özelliklerini Ayarlamak:
1. Her bir sekmenin adını, simgesini ve diğer özelliklerini özelleştirebilirsiniz.
2. Tab bar denetleyicinizin özelliklerini düzenlemek için Storyboard'da ilgili sekme öğesini seçin ve Sağdaki Özellikler İnpektörünü kullanarak ayarlamalar 
yapın.
İlk Görünümü Belirlemek:
1. Genellikle, uygulamanızı başlattığınızda hangi sekmenin görünmesini istediğinizi belirlemelisiniz. Bu, tab bar denetleyicinizin "Selected View Controller" özelliğiyle yapılır.
Geçişler ve Etkileşimler:
1. Kullanıcılar farklı sekmelere tıkladığında görünüm değişiklikleri yapmak için geçişleri ve etkileşimleri ele almalısınız. Bu, görünümler arasında geçiş yapmak için programlama gerektirebilir.
Uygulamayı Test Etme:
1. Projeyi simülatörde veya bir gerçek cihazda çalıştırarak sekme çubuğunun nasıl davrandığını test edin.

Swift ve UIKit kullanarak tab bar eklemek oldukça yaygın bir uygulama yapma görevidir. Uygulamanızın gereksinimlerine ve tasarımına bağlı olarak, tab barı
daha karmaşık şekilde özelleştirebilirsiniz. Ayrıca, her bir sekme için ilgili görünüm denetleyicilerini özelleştirmeniz gerekebilir. Bu adımlar, temel birtab bar uygulaması oluşturmanıza yardımcı olacaktır.
