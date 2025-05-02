# UIMedalGroupView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `RectTransform _frameContainer`

- `RectTransform _tokenContainer`

- `UIMedalGroupTokenView _tokePrefab`

- `Sprite _diyDefaultTokenBkg`

- `UIPage page`

- `DIYViewCache m_diyCache`

- `GroupViewCache m_groupCache`

- `UIMedalDIYFrame m_diyFrame`

- `UIMedalGroupFrame m_groupFrame`


## Methods

- `Void UpdateStatus(DIYOptions)`

- `Void UpdateStatus(GroupOptions)`

- `Void _UpdateDIY(DIYOptions)`

- `Void _UpdateGroup(GroupOptions)`

- `Void _LoadTokenConfigFromDIY(DIYViewCache, UIMedalDIYFrame)`

- `Void _LoadTokenConfigFromGroup(GroupViewCache, UIMedalGroupFrame)`

- `Void _UpdateTokenViews()`

- `UIMedalGroupTokenView _CreateTokenView()`

- `Void _RecollectGraphics()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalGroupView : MonoBehaviour, IHotfixable
{
	private RectTransform _frameContainer; // 0x18
	private RectTransform _tokenContainer; // 0x20
	private UIMedalGroupTokenView _tokePrefab; // 0x28
	private Sprite _diyDefaultTokenBkg; // 0x30
	private List`1 m_tokenViews; // 0x38
	private List`1 m_tokenConfigs; // 0x40
	private List`1 m_sharedDIYPosList; // 0x48
	private UIPage page; // 0x50
	private List`1 m_graphics; // 0x58
	private DIYViewCache m_diyCache; // 0x60
	private GroupViewCache m_groupCache; // 0x90
	private UIMedalDIYFrame m_diyFrame; // 0xa0
	private UIMedalGroupFrame m_groupFrame; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x0
	private static DelegateBridge __Hotfix1_UpdateStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetGraphics; // 0x10
	private static DelegateBridge __Hotfix0__UpdateDIY; // 0x18
	private static DelegateBridge __Hotfix0__UpdateGroup; // 0x20
	private static DelegateBridge __Hotfix0__LoadTokenConfigFromDIY; // 0x28
	private static DelegateBridge __Hotfix0__LoadTokenConfigFromGroup; // 0x30
	private static DelegateBridge __Hotfix0__UpdateTokenViews; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfMedalAchieved; // 0x40
	private static DelegateBridge __Hotfix0__LoadProperMedalData; // 0x48
	private static DelegateBridge __Hotfix0__DestroyFrame; // 0x50
	private static DelegateBridge __Hotfix0__CreateTokenView; // 0x58
	private static DelegateBridge __Hotfix0__RecollectGraphics; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x278ee88 VA: 0x7594da6e88
	public Void UpdateStatus(DIYOptions options) { }
	// RVA: 0x278f790 VA: 0x7594da7790
	public Void UpdateStatus(GroupOptions options) { }
	// RVA: 0x278f8a0 VA: 0x7594da78a0
	public List`1 GetGraphics() { }
	// RVA: 0x278ef98 VA: 0x7594da6f98
	private Void _UpdateDIY(DIYOptions options) { }
	// RVA: 0x278f2b0 VA: 0x7594da72b0
	private Void _UpdateGroup(GroupOptions options) { }
	// RVA: 0x278fd58 VA: 0x7594da7d58
	private Void _LoadTokenConfigFromDIY(DIYViewCache viewCache, UIMedalDIYFrame frame) { }
	// RVA: 0x27908d0 VA: 0x7594da88d0
	private Void _LoadTokenConfigFromGroup(GroupViewCache viewCache, UIMedalGroupFrame frame) { }
	// RVA: 0x2790414 VA: 0x7594da8414
	private Void _UpdateTokenViews() { }
	// RVA: 0x2790da8 VA: 0x7594da8da8
	private static Boolean _CheckIfMedalAchieved(String medalId, Func`2 overrideCheckMethod) { }
	// RVA: 0x2790bf4 VA: 0x7594da8bf4
	private static MedalPerData _LoadProperMedalData(String medalId, Func`2 overrideCheckMethod) { }
	// RVA: 0x2790e70 VA: 0x7594da8e70
	private static Void _DestroyFrame(GameObject gameObject) { }
	// RVA: 0x2790cfc VA: 0x7594da8cfc
	private UIMedalGroupTokenView _CreateTokenView() { }
	// RVA: 0x278f5cc VA: 0x7594da75cc
	private Void _RecollectGraphics() { }
	// RVA: 0x2790f30 VA: 0x7594da8f30
	public Void .ctor() { }
}
```