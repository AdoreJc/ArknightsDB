# Act5D1RuneStageDetailContainer

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1RuneStageDetailText _detailText`

- `SimpleLayoutContent _container`

- `CanvasGroup _newHandObj`

- `CanvasGroup _warningObj`

- `String m_cacheRuneReId`

- `Boolean m_isInited`

- `FadeSwitchTween m_newHandSwitch`

- `FadeSwitchTween m_warningSwitch`

- `DetailAdapter m_detailAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _Render(String, List`1)`

- `Void _RenderWarningInfo(Boolean)`

- `Void Render(String, List`1, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneStageDetailContainer : MonoBehaviour, IHotfixable
{
	private Act5D1RuneStageDetailText _detailText; // 0x18
	private SimpleLayoutContent _container; // 0x20
	private CanvasGroup _newHandObj; // 0x28
	private CanvasGroup _warningObj; // 0x30
	private String m_cacheRuneReId; // 0x38
	private Boolean m_isInited; // 0x40
	private FadeSwitchTween m_newHandSwitch; // 0x48
	private FadeSwitchTween m_warningSwitch; // 0x50
	private DetailAdapter m_detailAdapter; // 0x58
	private List`1 m_displayRuneList; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderWarningInfo; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31cb1f4 VA: 0x75957e31f4
	private Void _InitIfNot() { }
	// RVA: 0x31cb434 VA: 0x75957e3434
	private Void _Render(String runeReId, List`1 runeList) { }
	// RVA: 0x31cb6c0 VA: 0x75957e36c0
	private Void _RenderWarningInfo(Boolean isWarning) { }
	// RVA: 0x31cb74c VA: 0x75957e374c
	public Void Render(String runeReId, List`1 runeInfo, Boolean isWarning) { }
	// RVA: 0x31cb7f8 VA: 0x75957e37f8
	public Void .ctor() { }
}
```