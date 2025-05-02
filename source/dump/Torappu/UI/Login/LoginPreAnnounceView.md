# LoginPreAnnounceView

**Namespace:** `Torappu.UI.Login`


## Fields

- `GameObject _renderObj`

- `Text _titleText`

- `Text _confirmButtonText`

- `SimpleLayoutContent _layoutContent`

- `Action m_finishCb`

- `Adatper m_adapter`


## Methods

- `Void ClosePanel()`

- `Void _RenderAnnounce(PreAnnounceConfigData, Action)`

- `Void <ClosePanel>b__12_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Login
public class LoginPreAnnounceView : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Single FINISH_CB_DELAY; // 0x0
	private GameObject _renderObj; // 0x18
	private Text _titleText; // 0x20
	private Text _confirmButtonText; // 0x28
	private SimpleLayoutContent _layoutContent; // 0x30
	private Action m_finishCb; // 0x38
	private Adatper m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_TryLaunchPreAnnounce; // 0x8
	private static DelegateBridge __Hotfix0_TestOnlyLaunchPreAnnounce; // 0x10
	private static DelegateBridge __Hotfix0__LaunchPreAnnounce; // 0x18
	private static DelegateBridge __Hotfix0_ClosePanel; // 0x20
	private static DelegateBridge __Hotfix0__RenderAnnounce; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x27b2aa4 VA: 0x7594dcaaa4
	protected override Void OnInit() { }
	// RVA: 0x27afe30 VA: 0x7594dc7e30
	public static Void TryLaunchPreAnnounce(Action finishCB, Boolean forceOpen) { }
	// RVA: 0x27b2f90 VA: 0x7594dcaf90
	public static Void TestOnlyLaunchPreAnnounce() { }
	// RVA: 0x27b2d48 VA: 0x7594dcad48
	private static Void _LaunchPreAnnounce(Action finishCB, Boolean forceOpen) { }
	// RVA: 0x27b2ff8 VA: 0x7594dcaff8
	public Void ClosePanel() { }
	// RVA: 0x27b32a4 VA: 0x7594dcb2a4
	private Void _RenderAnnounce(PreAnnounceConfigData data, Action finishCB) { }
	// RVA: 0x27b34e8 VA: 0x7594dcb4e8
	public Void .ctor() { }
	// RVA: 0x27b3578 VA: 0x7594dcb578
	private Void <ClosePanel>b__12_2() { }
}
```