<template>
	<div>
		<header-slider-by-button :images="images"/>
		<div class="start-intro" style="">
			<div class="wrapper">
				<div class="start-intro__title dastnevis">ساعاتی خوش با فوتبال دستی</div>
				<p class="start-intro__text dastnevis"> فوتبال دستی از بازی های نوستالژی و دوست داشتنی تمام افراد دنیا
					اعم از بانوان
					و
					آقایان
					می
					باشد که قدر مسلم اغلب ما موفق به کسب تجربه بازی با آن شده ایم. امروزه دنیای فوتبال دستی ها
					کاملا پیشرفت کرده و می توان در کنار مدل های ساده پیشین با مدل های فوق العاده جذابی نیز از
					این نوع میزهای ورزشی و تفریحی مواجه شویم که البته این تنوع مدلی سبب قدری پیچیده شدن خرید
					فوتبال دستی برای عاشقان این بازی شده است. با این حال ما تصمیم داریم تا در این مقاله شما را
					با یکسری از نکات مهم در خصوص خرید فوتبال دستی آشنا نماییم که قطعا به کارتان خواهد آمد.</p>
			</div>
		</div>

			<div class="parent-items space">
				<div class="parent-items__parent-logo">
					<logo/>
				</div>
				<div class="title-items">انواع فوتبال دستی</div>
				<div class="space"></div>
		<div class="wrapper">
				<div class="parent-items__items">
					<div class="parent-items__item" v-for="(foosball,index) in foosball1" :key="index">
						<card-intro :product="foosball"/>
					</div>
				</div>
		</div>
			</div>



		<div class="background-article" :style="{backgroundImage: `url(images/header/12.jpg)`}">
			<div class="wrapper">
				<div class="space"></div>
				<div class="title-items" style="color : #ffffff">نکات مهم هنگام خرید فوتبال دستی</div>
				<div class="space"></div>
				<div class="background-article__pages">
					<div class="background-article__page">
						<p><span class="bold">نوع محصول:</span> مثل همیشه اولین نکته ای که هنگام خرید فوتبال دستی باید
							به آن توجه کنید، نوع آن است. میزهای فوتبال دستی امروزه دارای انواع و اقسام مدل های نشسته،
							ایستاده و همچنین ژتون خور (مناسب برای باشگاه های ورزشی) می باشد و انتخاب یک کدام از این مدل
							ها فقط و فقط بستگی به سن افراد استفاده کننده و همچنین فضای مدنظر شما خواهد داشت.</p>
						<p><span class="bold">قابلیت تنظیم ارتفاع:</span> این مورد تنها برای میز فوتبال دستی ایستاده
							صِدق می کند و یقینا مدل نشسته و بدون پایه این محصول هیچ نیازی به انجام تنظیم ارتفاع جهت
							اجرای بازی ندارد. شما می توانید با در نظر داشتن این نکته، فوتبال دستی را خریداری نمایید که
							در هر موقعیت مکانی و زمانی ارتفاع پایه های آن را تغییر داده و متناسب با قد کسانی که قصد بازی
							با آن را کرده اند، قرار دهید.</p>
						<p><span class="bold">ابعاد آن:</span> بطور کلی فوتبال دستی ها باید در ابعاد استاندارد ۱۴۰ سانتی
							متر طول، ۷۵ سانتی متر عرض و همچنین ۹۰ سانتی متر ارتفاع ساخته شده باشند که خوب البته با توجه
							به مدل های ارزان و غیر استانداری که امروزه در بازار به فراوانی یافت می شود، باید گفت خیلی هم
							نباید بر روی این میزان اندازه ها دقیق شد! با این حال توجه داشته باشید که استقرار فوتبال دستی
							در هر نقطه ای از داخل و یا خارج از خانه شما باید متناسب با یک فضای مناسب جهت حرکت آزادانه
							بازیکنان و همچنین عقب و جلو کردن راحت میله های مخصوص بازی برایتان صورت بگیرد.</p>
						<p><span class="bold">کیفیت خطوط صفحه بازی:</span> از دیگر نکاتی که حتما باید به هنگام انتخاب و
							خرید یک فوتبال دستی باکیفیت به آن توجه داشته باشید، ماندگاری خطوطی است که بر روی صفحه بازی
							نقش بسته اند. میزهای غیر استاندارد و بی کیفیت امروزه از کیفیت خطوط بسیار ناچیزی برخوردار
							هستند و با گذشت کمی زمان، خطوط آن ها از روی میز پاک و سبب سردرگمی شما در حین بازی با محصول
							ورزشی و تفریحی مد نظرتان خواهد شد.</p>
						<p><span class="bold">جنس بدنه:</span> بطور کلی فوتبال دستی ها یا از جنس چوب طبیعی ساخته می شوند
							که خوب قطعا گران قیمت خواهند بود و یا اینکه برای ساخت و تولید آنان از چوب MDF و یا پلاستیک
							های مقاوم استفاده می کنند که به ترتیب قیمت نهایی آنان ارزانتر از چوب طبیعی خواهد بود.
							حواستان باشد فوتبال دستی یک بازی پُر فشار است که در صورت عدم وجود مرغوبت کافی در جنس بدنه
							آن، شما را از انجام بازی با خود پشیمان خواهد کرد.</p>
						<div class="page-number">صفحه یک</div>
					</div>
					<div class="background-article__page">
						<p><span class="bold">نوع میله های بازی:</span> توجه به نوع میله های به کار رفته در فوتبال دستی
							نیز از دیگر نکات مهمی است که باید به آن توجه داشته باشید. برای کسانی که به دنبال انجام
							فوتبال دستیِ سرعتی هستند، میله های فلزی توخالی مناسب تر است و برای کسانی که به دنبال زدن
							ضرباتی دقیق اما آهسته می گردند، خرید فوتبال دستی هایی که دارای میله های فلزی توپُر می باشند،
							توصیه می شود. ناگفته نماند جنس دستگیره نصب شده بر سر این نوع از میله نیز از دیگر موارد مهمی
							است که بهتر است به آن توجه نمایید.</p>
						<p><span class="bold">کیفیت آدمک ها:</span> کیفیت آدمک های نصب شده بر روی میله های بازی نیز از
							دیگر نکاتی است که باید به آن توجه داشته باشید. بهتر است اگر از دسته بازیکن های قدرتی هستید
							به فکر خرید فوتبال دستی با آدمک های فلزی که از وزن به مراتب سنگین تری نیز برخوردار می باشند،
							باشید و در صورتی که از دسته بازیکنان سرعتی هستید، به دنبال خرید محصولی با آدمک های پلاستیکی
							و سبک وزن باشید.</p>
						<p><span class="bold">تعداد دروازه بان ها:</span> فوتبال دستی های کنونی در ۲ سیستم تک دروازه
							بانی و یا سه دروازه بانی از سوی کمپانی های تولید کننده ساخته می شوند که انتخاب یک کدام از
							این دو طرح کلی تنها بسته به سلیقه و سبک بازی شما دارد و صرفا ما برای افزایش اطلاعات شما در
							خصوص این نوع از محصولات ورزشی و تفریحی به این نکته قابل توجه اشاره نموده ایم.</p>
						<p><span class="bold">قیمت فوتبال دستی:</span> قیمت فوتبال دستی می تواند از چند صد هزار تومان
							آغاز و تا چندین میلیون تومان نیز ادامه پیدا کند. عوامل زیادی را می توان نام برد که بر روی
							قیمت این محصول ورزشی تاثیر گذار است اما شاید مهمترین نکته ای که هنگام خرید آن باید به آن دقت
							داشته باشید، نوع نیاز، تعداد بازیکنان و همچنین سن آنان می باشد.</p>
						<p>تا اینجا با چند نکته درباره انتخاب و خرید فوتبال دستی مناسب آشنا شدیم. در ادامه لیستی از چند
							فوتبال دستی ارزان، با کیفیت و محبوب در بازار ایران را برای شما آماده کرده‌ایم. همه این
							فوتبال دستی‌ها از کیفیت بالا و قیمت مناسبی برخوردار هستند. فراموش نکنید که با کلیک روی تصویر
							یا دکمه هر آیتم، می‌توانید تصاویر و اطلاعات بیشتری را درباره محصول به دست بیاورید.</p>
						<div class="page-number">صفحه دو</div>
					</div>
				</div>
			</div>
		</div>

		<div class="container-cards">
			<div class="wrapper">
				<div class="title-items">آشنایی با محصولات آسیا</div>
				<div class="space"></div>
				<div class="cards">
					<div class="cards__card" v-for="(product,index) in products" :key="index">
						<card :product="product"/>
					</div>
				</div>

				<div class="spinner" v-if="products.length == 0">
					<img width="90" height="60" src="../../../public/images/gif/spinner.gif">
				</div>
			</div>
		</div>

		<div class="wrapper">
			<div class="article space">
				<div class="article__image" :style="{backgroundImage : `url(images/articles/6.jpg)`}">
					<div class="article__image--ratio"></div>
				</div>
				<div class="article__text">
					<div class="title-items">خاطرات ماندگار</div>
					<div class="article__intro">
						<p> فوتبال دستی از بازی های نوستالژی و دوست داشتنی تمام افراد دنیا اعم از بانوان و آقایان می
							باشد که قدر مسلم اغلب ما موفق به کسب تجربه بازی با آن شده ایم. امروزه دنیای فوتبال دستی ها
							کاملا پیشرفت کرده و می توان در کنار مدل های ساده پیشین با مدل های فوق العاده جذابی نیز از
							این نوع میزهای ورزشی و تفریحی مواجه شویم که البته این تنوع مدلی سبب قدری پیچیده شدن خرید
							فوتبال دستی برای عاشقان این بازی شده است. با این حال ما تصمیم داریم تا در این مقاله شما را
							با یکسری از نکات مهم در خصوص خرید فوتبال دستی آشنا نماییم که قطعا به کارتان خواهد آمد.</p>
						<p> فوتبال دستی از بازی های نوستالژی و دوست داشتنی تمام افراد دنیا اعم از بانوان و آقایان می
							باشد که قدر مسلم اغلب ما موفق به کسب تجربه بازی با آن شده ایم. امروزه دنیای فوتبال دستی ها
							کاملا پیشرفت کرده و می توان در کنار مدل های ساده پیشین با مدل های فوق العاده جذابی نیز از
							این نوع میزهای ورزشی و تفریحی مواجه شویم که البته این تنوع مدلی سبب قدری پیچیده شدن خرید
							فوتبال دستی برای عاشقان این بازی شده است. با این حال ما تصمیم داریم تا در این مقاله شما را
							با یکسری از نکات مهم در خصوص خرید فوتبال دستی آشنا نماییم که قطعا به کارتان خواهد آمد.</p>
					</div>
				</div>
			</div>
		</div>

		<div class="parent-items space">
			<div class="parent-items__parent-logo">
				<logo/>
			</div>
			<div class="title-items">انواع فوتبال دستی</div>
			<div class="space"></div>
			<div class="wrapper">
			<div class="parent-items__items">
				<div class="parent-items__item" v-for="(foosball,index) in foosball2" :key="index">
					<card-intro :product="foosball"/>
				</div>
			</div>
			</div>
		</div>
	</div>
</template>

<script>
    import axios from 'axios';
    import Logo from "../../components/Logo";
    import CardIntro from "../../components/CardIntro/index";
    import Card from "../../components/Card/index";
    import HeaderSliderByButton from "../../components/HeaderSliderByButton/index";


    export default {
        name: "Index",

        components: {
            HeaderSliderByButton,
            CardIntro,
            Card,
            Logo,
        },

        data() {
            return {
                foosball2: [
                    {
                        image: 'spain.jpg',
                        title: 'فوتبال دستی اسپانیایی',
                        text: 'میزهای فوتبال اسپانیا کاملاً منحصر به فرد هستند و به شدت از فوتبال مردان اسپانیایی الهام گرفته اند و بنابراین خط هافبک را جنبه غالب می دانند و در نتیجه ، میزهای کفش به شکل "U" به سمت وسط شیب دارد. این امر باعث می شود خط میانی بیشتر توپ ها را به دست آورد و از پین پشت به عنوان اصلی ترین روش برای کنترل توپ استفاده کند. جالب است ، اما عادت کردن سخت است!'
                    },
                    {
                        image: 'germany.jpg',
                        title: 'فوتبال دستی آلمانی',
                        text: 'یکی دیگر از سبک های اصلی بازی ، فوتبالیست آلمانی را می توان ترکیبی از عمل گرایی آمریکایی همراه با ظرافت اروپایی توصیف کرد. مجسمه های آلمانی بسیار شبیه آمریکایی ها طراحی شده اند ، اما سبک تر هستند ، در نتیجه به سنجاق بهتر می انجامد. روش جمع بندی این سبک بازی نسبتاً سریع است ، با کنترل خوب و یک بازی سازگار/ قابل پیش بینی تر.'
                    },
                    {
                        image: 'iteli.jpg',
                        title: 'فوتبال دستی ایتالیایی',
                        text: 'برخلاف تیم واقعی مردان ایتالیا ، فوتسال فوتبال ایتالیا با سرعت بسیار زیادی انجام می شود و برخی قوانین محلی حتی اگر توپ در یک ثانیه در جدول متوقف شود ، آن را خطا می دانند. برخلاف کنترل محاسبه شده ، تأکید بیشتری بر بازتاب و سرعت فکر می شود و بنابراین ، اغلب میزهای ایتالیایی مجهز به زمین بازی شیشه ای ، مجسمه های کوچک تر و میله های سبک تر هستند. در نتیجه نوع بازی ایتالیایی یک بازی هیجان انگیز ، متنوع و مناسب برای بازیکنان با تمام سطوح مهارت است.'
                    },
                    {
                        image: 'france.jpg',
                        title: 'فوتبال دستی فرانسوی',
                        text: 'از هر یک از فرانسوی ها بپرسید که میز فوتبال خوب چیست و پاسخ بی چون و چرای آن "پای بچه" است. این به سبک فرانسوی میز اشاره می کند - مجسمه های آلومینیومی سنگین ، زمین بازی لاستیکی و توپ های چوب پنبه ای سبک. و البته در رنگهای فرانسوی! همه این عوامل به یک بازی که در کنترل توپ بی نظیر است و مهارت بالایی دارد کمک می کند. به عنوان یک طرف ، میزهای اصیل فرانسوی همیشه توسط صنعتگران ساخته می شوند و به عنوان با دوام ترین میزهای جهان شناخته می شوند.'
                    },
                ],
                foosball1: [
                    {
                        image: '8.jpg',
                        title: 'فوتبال دستی خانگی',
                        text: 'فوتبال دستی  جالب است زیرا می توانید در خانه از نظر فنی بدون هیچ گونه کار فیزیکی اما فقط با استفاده از دست و ذهن خود فوتبال بازی کنید.'
                    },
                    {
                        image: '9.jpg',
                        title: 'فوتبال دستی حرفه ای',
                        text: 'برخی از مدلها بسیار بهتر از بقیه هستند و اینهایی هستند که می توان آنها را به عنوان میزهای حرفه ای فوتبال طبقه بندی کرد. این میزها که میز مسابقات فوتبال نیز نامیده می شوند از مواد باکیفیت عالی ساخته شده اند تا بازی عالی را ارائه دهند.'
                    },
                    {
                        image: '11.jpg',
                        title: 'فوتبال دستی تاشو',
                        text: 'گر شما همیشه می خواهید یک میز فوتسبال داشته باشید اما فضای زیادی برای وقت گذاشتن ندارید ، یک میز فولاد تاشو یک گزینه عالی است. هنگامی که از آنها استفاده نمی کنید ، ذخیره آنها آسان است و حتی می توانید مدلهایی با اندازه استاندارد پیدا کنید. به علاوه ، در واقع تنوع زیادی وجود دارد.'
                    },
                    {
                        image: 'american.jpg',
                        title: 'فوتبال دستی آمریکایی',
                        text: 'تنها نوع میزهایی که 13 مجسمه را در یک زمین بازی ارائه می دهند در مقابل 11 میز یک طرفه ، شما بیشتر حدس می زنید-آمریکایی ها. به طور معمول در یک زمین بازی چند لایه پلاستیکی با مجسمه های پهن بازی می شود ، تأکید بر ارسال توپ است و از این نظر ، میزهای آمریکایی از بهترین ها هستند. گیم پلی در نتیجه پاهای بزرگتر ، به یک امر کندتر تبدیل می شود و به نظر ما ، بیشتر مورد علاقه علاقه مندان با گیم پلی آهسته و کنترل شده است.'
                    },

                ],

                images: [
                    // {
                    //     id: 0,
                    //     address: '0.jpg',
                    //     title: 'فوتبال دستی آسیا',
                    //     text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد'
                    // },
                    // {
                    //     id: 1,
                    //     address: '1.jpg',
                    //     title: 'بازی و سرگرمی',
                    //     text: 'و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    // },
                    {
                        id: 2,
                        address: '2.jpg',
                        title: 'فوتبال دستی آسیا',
                        text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.'
                    },
                    // {
                    //     id: 3,
                    //     address: '3.jpg',
                    //     title: 'دوستی و صممیت',
                    //     text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    // },
                    // {
                    //     id: 4,
                    //     address: '4.jpg',
                    //     title: 'فوتبال دستی آسیا',
                    //     text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    // },
                    // {
                    //     id: 5,
                    //     address: '5.jpg',
                    //     title: 'ساعاتی به دور از دقدقه',
                    //     text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.'
                    // },
                    // {
                    //     id: 6,
                    //     address: '6.jpg',
                    //     title: 'فوتبال دستی آسیا',
                    //     text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    // },
                    {
                        id: 7,
                        address: '7.jpg',
                        title: 'لذت فوتبال دستی',
                        text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.'
                    },
                    {
                        id: 8,
                        address: '8.jpg',
                        title: 'خاطراتی شیرین',
                        text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    },
                    // {
                    //     id: 9,
                    //     address: '9.jpg',
                    //     title: 'حرفه ای ها چگونه اند',
                    //     text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.'
                    // },
                    // {
                    //     id: 10,
                    //     address: '10.jpg',
                    //     title: 'فوتبال دستی آسیا',
                    //     text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    // },
                    {
                        id: 11,
                        address: '11.jpg',
                        title: 'تمرکز بالا',
                        text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.'
                    },
                    {
                        id: 12,
                        address: '12.jpg',
                        title: 'ارسال رایگان',
                        text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    },
                    {
                        id: 13,
                        address: '13.jpg',
                        title: 'فوتبال دستی آسیا',
                        text: 'لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ، و با استفاده از طراحان گرافیک است، چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است، و برای شرایط فعلی تکنولوژی مورد نیاز، و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد، کتابهای زیادی در شصت و سه درصد گذشته حال و آینده، شناخت فراوان جامعه و متخصصان را می طلبد، تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی، و فرهنگ پیشرو در زبان فارسی ایجاد کرد، در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها، و شرایط سخت تایپ به پایان رسد و زمان مورد نیاز شامل حروفچینی دستاوردهای اصلی، و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.'
                    },
                    // {
                    //     id: 14,
                    //     address: '14.jpg',
                    //     title: 'درباره ما',
                    //     text: 'ما باور داریم که کاربران ایرانی لایق بهترین‌ها هستند، از این رو ما تمام تلاش خود را می‌کنیم تا بتوانیم فیلم‌ها و مقالات آموزشی بروز و کاربردی را در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین‌ها در صنعت طراحی و برنامه‌نویسی وب شوید. ما ادعا نمی‌کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می‌کنیم بهترین عملکرد را به شما ارائه دهیم.'
                    // },
                ],
                products: [],

            }
        },


        mounted() {
            const vm = this;
            axios.get(process.env.VUE_APP_BASE_URL + 'products').then(res => {
                vm.products = res.data;
            })
        }
    }
</script>

<style scoped lang="scss">
	@import "index";

</style>
