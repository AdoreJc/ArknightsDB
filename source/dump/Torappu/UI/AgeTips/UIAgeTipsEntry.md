# UIAgeTipsEntry

**Namespace:** `Torappu.UI.AgeTips`


## Fields

- `Image _image`

- `Config _config`

- `UIAgeTipsDetailView _detailView`

- `Boolean m_isInited`


## Methods

- `Void Start()`

- `Void Init()`

- `Void OnDetailClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.AgeTips
public class UIAgeTipsEntry : MonoBehaviour, IHotfixable
{
	private Image _image; // 0x18
	private Config _config; // 0x20
	private UIAgeTipsDetailView _detailView; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnDetailClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2e991f0 VA: 0x75954b11f0
	private Void Start() { }
	// RVA: 0x2e9927c VA: 0x75954b127c
	public Void Init() { }
	// RVA: 0x2e99314 VA: 0x75954b1314
	public Void OnDetailClicked() { }
	// RVA: 0x2e993a0 VA: 0x75954b13a0
	public Void .ctor() { }
}
```