
<html lang="ko">
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<title>쥬니버 모바일 배포</title>
		<link rel="stylesheet" href="http://code.jquery.com/mobile/1.0.1/jquery.mobile-1.0.1.min.css" />
		<script src="http://code.jquery.com/jquery-1.6.4.min.js"></script>
		<script src="http://code.jquery.com/mobile/1.0.1/jquery.mobile-1.0.1.min.js"></script>
	</head>
	<body>
		<div data-role="page" id="ios" data-add-back-btn="true">
			<div data-role="header">
				<h1>쥬니버 모바일 배포</h1>
			</div>
			<div data-role="content">
                <a href="http://flashdev.naver.com/FlashUILab/Project/JuniorNaver/mobileapp/test/JuniverAndroid.apk" data-role="button" data-icon="star" data-theme="b" rel="external">Android 다운로드</a>
                <a href="itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/twipixel/deploy/master/naver/jr/com.nhncorp.jr.beta.plist" data-role="button" data-icon="star" data-theme="b" rel="external">iOS 다운로드</a>
                <a href="http://flashdev.naver.com/FlashUILab/Project/JuniorNaver/mobileapp/test/JuniverDesktop.air" data-role="button" data-icon="star" data-theme="b" rel="external">Desktop 다운로드</a>
                <a href="http://flashdev.naver.com/FlashUILab/Project/JuniorNaver/mobileapp/test/NHN_InHouse_Distribution_Provisioning_Profile.mobileprovision" data-role="button" data-icon="star" data-theme="b" rel="external">인증서 설치</a>
				<a href="http://flashdev.naver.com/FlashUILab/Project/JuniorNaver/mobileapp/test/JrAndroidTest.apk" data-role="button" data-icon="star" data-theme="c" rel="external">쥬니버용 다른 테스트 앱 다운로드 (for Android)</a>
				<a href="itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/twipixel/deploy/master/naver/jr/com.nhncorp.jr.test.plist" data-role="button" data-icon="star" data-theme="c" rel="external">쥬니버용 다른 테스트 앱 다운로드 (for iOS)</a>
				<a href="itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/twipixel/deploy/master/naver/jr/com.nhncorp.jr.beta.plist" data-role="button" data-icon="star" data-theme="b" rel="external">iOS 디버그용 다운로드</a>
			</div>
		</div>
	</body>
</html>
