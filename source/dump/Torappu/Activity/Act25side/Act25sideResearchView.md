# Act25sideResearchView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Text _researchCount`

- `SimpleLayoutContent _areaItemContent`

- `Act25sideResearchAreaView _areaViewPrefab`

- `Transform _areaViewContainer`

- `GameObject _panelCount`

- `GameObject _panelMax`

- `GameObject _panelAllComplete`

- `GameObject _panelUnComplete`

- `Boolean m_isInited`

- `Boolean m_hasPlayedEnterAnim`

- `AreaAdapter m_adapter`

- `UIPage m_page`

- `Act25sideResearchViewModel m_cachedViewModel`

- `Act25sideResearchAreaView m_areaView`


## Methods

- `Void Init(UIPage)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchView : DataBinder`1
{
	private Text _researchCount; // 0x20
	private SimpleLayoutContent _areaItemContent; // 0x28
	private Act25sideResearchAreaView _areaViewPrefab; // 0x30
	private Transform _areaViewContainer; // 0x38
	private GameObject _panelCount; // 0x40
	private GameObject _panelMax; // 0x48
	private GameObject _panelAllComplete; // 0x50
	private GameObject _panelUnComplete; // 0x58
	private Boolean m_isInited; // 0x60
	private Boolean m_hasPlayedEnterAnim; // 0x61
	private AreaAdapter m_adapter; // 0x68
	private UIPage m_page; // 0x70
	private Act25sideResearchViewModel m_cachedViewModel; // 0x78
	private Act25sideResearchAreaView m_areaView; // 0x80
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x327cc80 VA: 0x7595894c80
	public Void Init(UIPage page) { }
	// RVA: 0x3285c84 VA: 0x759589dc84
	public override Void OnValueChanged(Act25sideResearchProperty property) { }
	// RVA: 0x3285e7c VA: 0x759589de7c
	private Void _InitIfNot() { }
	// RVA: 0x32860dc VA: 0x759589e0dc
	public Void .ctor() { }
}
```