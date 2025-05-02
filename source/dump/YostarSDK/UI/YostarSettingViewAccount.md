# YostarSettingViewAccount

**Namespace:** `YostarSDK.UI`


## Fields

- `GameObject _panelGenMigrateCode`

- `GameObject _titleGenMigrateCode`

- `GameObject _panelDeleteAccount`

- `YostarSDKAccountBindNotifyView _accountBindSucNotify`

- `TwoStateToggle _toggleBindTW`

- `Text _textAccountTW`

- `TwoStateToggle _toggleBindFB`

- `Text _textAccountFB`

- `TwoStateToggle _toggleBindYostar`

- `Text _textAccountYostar`

- `TwoStateToggle _toggleBindGoogle`

- `Text _textAccountGoogle`

- `TwoStateToggle _toggleBindApple`

- `Text _textAccountApple`

- `Text _textFacebook`

- `Text _textTwitter`

- `Text _textYostar`

- `Text _textGoogle`

- `Text _textApple`

- `Text _textAccountTip`

- `Text _textLogout`

- `Text _textBtnLogout`

- `Text _textDeleteAccount`

- `Text _textBtnDeleteAccount`

- `Text _textMigrationCode`

- `Text _textBtnMigrationCode`

- `Text _textAgreementType1`

- `Text _textAgreementType2`

- `YostarSDK m_sdk`


## Methods

- `Void Render(YostarSDK)`

- `Void _UpdateWidgets()`

- `Void _RenderConstTexts()`

- `Void EventOnBindTW()`

- `Void EventOnUnbindTW()`

- `Void EventOnBindFB()`

- `Void EventOnUnbindFB()`

- `Void EventOnBindApple()`

- `Void EventOnUnbindApple()`

- `Void EventOnBindYostar()`

- `Void EventOnUnbindYostar()`

- `Void EventOnBindGoogle()`

- `Void EventOnUnbindGoogle()`

- `Void EventOnLogoutClicked()`

- `Void EventOnMigrationCodeClicked()`

- `Void EventOnDeleteAccountClicked()`

- `Void EventOnAgreement1()`

- `Void EventOnAgreement2()`

- `Void _OnBackFromPopupPage()`

- `Void _BindYostar()`

- `Void _UnbindYostar()`

- `Void _BindThirdParty(LoginPlatform)`

- `Void _UnbindThirdParty(LoginPlatform)`

- `Void _SocialLinkCallback(LinkRet)`

- `Void _SocialUnlinkCallback(UnLinkRet)`

- `Boolean _CheckIfValidToUnbind()`

- `Void _DeleteAccountCallback(DeleteAccountRet)`

- `Void _BindRelatedNotify(String)`

- `Boolean _CheckIfAccountSync()`

- `Void <EventOnDeleteAccountClicked>b__47_0()`

- `Void <EventOnDeleteAccountClicked>b__47_1()`

- `Void <_UnbindYostar>b__54_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class YostarSettingViewAccount : MonoBehaviour, IHotfixable
{
	private GameObject _panelGenMigrateCode; // 0x18
	private GameObject _titleGenMigrateCode; // 0x20
	private GameObject _panelDeleteAccount; // 0x28
	private YostarSDKAccountBindNotifyView _accountBindSucNotify; // 0x30
	private TwoStateToggle _toggleBindTW; // 0x38
	private Text _textAccountTW; // 0x40
	private TwoStateToggle _toggleBindFB; // 0x48
	private Text _textAccountFB; // 0x50
	private TwoStateToggle _toggleBindYostar; // 0x58
	private Text _textAccountYostar; // 0x60
	private TwoStateToggle _toggleBindGoogle; // 0x68
	private Text _textAccountGoogle; // 0x70
	private TwoStateToggle _toggleBindApple; // 0x78
	private Text _textAccountApple; // 0x80
	private Text[] _textsBind; // 0x88
	private Text[] _textsUnbind; // 0x90
	private Text _textFacebook; // 0x98
	private Text _textTwitter; // 0xa0
	private Text _textYostar; // 0xa8
	private Text _textGoogle; // 0xb0
	private Text _textApple; // 0xb8
	private Text _textAccountTip; // 0xc0
	private Text _textLogout; // 0xc8
	private Text _textBtnLogout; // 0xd0
	private Text _textDeleteAccount; // 0xd8
	private Text _textBtnDeleteAccount; // 0xe0
	private Text _textMigrationCode; // 0xe8
	private Text _textBtnMigrationCode; // 0xf0
	private Text _textAgreementType1; // 0xf8
	private Text _textAgreementType2; // 0x100
	private Text[] _textsBtnAgreement; // 0x108
	private YostarSDK m_sdk; // 0x110
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateWidgets; // 0x8
	private static DelegateBridge __Hotfix0__RenderConstTexts; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBindTW; // 0x18
	private static DelegateBridge __Hotfix0_EventOnUnbindTW; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBindFB; // 0x28
	private static DelegateBridge __Hotfix0_EventOnUnbindFB; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBindApple; // 0x38
	private static DelegateBridge __Hotfix0_EventOnUnbindApple; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBindYostar; // 0x48
	private static DelegateBridge __Hotfix0_EventOnUnbindYostar; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBindGoogle; // 0x58
	private static DelegateBridge __Hotfix0_EventOnUnbindGoogle; // 0x60
	private static DelegateBridge __Hotfix0_EventOnLogoutClicked; // 0x68
	private static DelegateBridge __Hotfix0_EventOnMigrationCodeClicked; // 0x70
	private static DelegateBridge __Hotfix0_EventOnDeleteAccountClicked; // 0x78
	private static DelegateBridge __Hotfix0_EventOnAgreement1; // 0x80
	private static DelegateBridge __Hotfix0_EventOnAgreement2; // 0x88
	private static DelegateBridge __Hotfix0_RaiseErrorForUnlink; // 0x90
	private static DelegateBridge __Hotfix0__GenAccountStatusText; // 0x98
	private static DelegateBridge __Hotfix0__OnBackFromPopupPage; // 0xa0
	private static DelegateBridge __Hotfix0__BindYostar; // 0xa8
	private static DelegateBridge __Hotfix0__UnbindYostar; // 0xb0
	private static DelegateBridge __Hotfix0__BindThirdParty; // 0xb8
	private static DelegateBridge __Hotfix0__UnbindThirdParty; // 0xc0
	private static DelegateBridge __Hotfix0__SocialLinkCallback; // 0xc8
	private static DelegateBridge __Hotfix0__SocialUnlinkCallback; // 0xd0
	private static DelegateBridge __Hotfix0__CheckIfValidToUnbind; // 0xd8
	private static DelegateBridge __Hotfix0__DeleteAccountCallback; // 0xe0
	private static DelegateBridge __Hotfix0__BindRelatedNotify; // 0xe8
	private static DelegateBridge __Hotfix0__CheckIfAccountSync; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8


	// RVA: 0x257ba6c VA: 0x7594b93a6c
	public Void Render(YostarSDK sdk) { }
	// RVA: 0x257bef4 VA: 0x7594b93ef4
	private Void _UpdateWidgets() { }
	// RVA: 0x257bb00 VA: 0x7594b93b00
	private Void _RenderConstTexts() { }
	// RVA: 0x257c4d0 VA: 0x7594b944d0
	public Void EventOnBindTW() { }
	// RVA: 0x257c750 VA: 0x7594b94750
	public Void EventOnUnbindTW() { }
	// RVA: 0x257ca00 VA: 0x7594b94a00
	public Void EventOnBindFB() { }
	// RVA: 0x257ca84 VA: 0x7594b94a84
	public Void EventOnUnbindFB() { }
	// RVA: 0x257cb08 VA: 0x7594b94b08
	public Void EventOnBindApple() { }
	// RVA: 0x257cb8c VA: 0x7594b94b8c
	public Void EventOnUnbindApple() { }
	// RVA: 0x257cc10 VA: 0x7594b94c10
	public Void EventOnBindYostar() { }
	// RVA: 0x257cd54 VA: 0x7594b94d54
	public Void EventOnUnbindYostar() { }
	// RVA: 0x257cf18 VA: 0x7594b94f18
	public Void EventOnBindGoogle() { }
	// RVA: 0x257cf9c VA: 0x7594b94f9c
	public Void EventOnUnbindGoogle() { }
	// RVA: 0x257d020 VA: 0x7594b95020
	public Void EventOnLogoutClicked() { }
	// RVA: 0x257d17c VA: 0x7594b9517c
	public Void EventOnMigrationCodeClicked() { }
	// RVA: 0x257d258 VA: 0x7594b95258
	public Void EventOnDeleteAccountClicked() { }
	// RVA: 0x257d340 VA: 0x7594b95340
	public Void EventOnAgreement1() { }
	// RVA: 0x257d41c VA: 0x7594b9541c
	public Void EventOnAgreement2() { }
	// RVA: 0x257a420 VA: 0x7594b92420
	public static Void RaiseErrorForUnlink(UnLinkRet ret, Action nextStep) { }
	// RVA: 0x257c394 VA: 0x7594b94394
	private static String _GenAccountStatusText(AccountInfo curAccount, LoginPlatform platform) { }
	// RVA: 0x257d4f8 VA: 0x7594b954f8
	private Void _OnBackFromPopupPage() { }
	// RVA: 0x257cc90 VA: 0x7594b94c90
	private Void _BindYostar() { }
	// RVA: 0x257cdd4 VA: 0x7594b94dd4
	private Void _UnbindYostar() { }
	// RVA: 0x257c554 VA: 0x7594b94554
	private Void _BindThirdParty(LoginPlatform platform) { }
	// RVA: 0x257c7d4 VA: 0x7594b947d4
	private Void _UnbindThirdParty(LoginPlatform platform) { }
	// RVA: 0x257d644 VA: 0x7594b95644
	private Void _SocialLinkCallback(LinkRet ret) { }
	// RVA: 0x257d898 VA: 0x7594b95898
	private Void _SocialUnlinkCallback(UnLinkRet ret) { }
	// RVA: 0x257d560 VA: 0x7594b95560
	private Boolean _CheckIfValidToUnbind() { }
	// RVA: 0x257da08 VA: 0x7594b95a08
	private Void _DeleteAccountCallback(DeleteAccountRet ret) { }
	// RVA: 0x257d7b8 VA: 0x7594b957b8
	private Void _BindRelatedNotify(String content) { }
	// RVA: 0x257d5c8 VA: 0x7594b955c8
	private Boolean _CheckIfAccountSync() { }
	// RVA: 0x257dc08 VA: 0x7594b95c08
	public Void .ctor() { }
	// RVA: 0x257dc78 VA: 0x7594b95c78
	private Void <EventOnDeleteAccountClicked>b__47_0() { }
	// RVA: 0x257dd10 VA: 0x7594b95d10
	private Void <EventOnDeleteAccountClicked>b__47_1() { }
	// RVA: 0x257ddd4 VA: 0x7594b95dd4
	private Void <_UnbindYostar>b__54_0() { }
}
```