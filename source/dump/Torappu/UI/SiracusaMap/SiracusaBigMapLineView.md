# SiracusaBigMapLineView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `RectTransform _frontContainer`

- `RectTransform _backContainer`

- `SiracusaBigMapLineItem _frontPrefab`

- `SiracusaBigMapLineItem _backPrefab`

- `Tools m_tools`

- `SiracusaMapFocusPolicy m_lastFocusPolicy`


## Methods

- `Void Init(Tools)`

- `Void Render(SiracusaMapPanelMapViewModel)`

- `Void _RebuildLines(SiracusaMapPanelMapViewModel)`

- `Void _RefreshAllLineItems(SiracusaMapFocusPolicy)`

- `LineItem _CreateNewLineItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapLineView : MonoBehaviour, IHotfixable
{
	private RectTransform _frontContainer; // 0x18
	private RectTransform _backContainer; // 0x20
	private SiracusaBigMapLineItem _frontPrefab; // 0x28
	private SiracusaBigMapLineItem _backPrefab; // 0x30
	private Tools m_tools; // 0x38
	private SiracusaMapFocusPolicy m_lastFocusPolicy; // 0x40
	private Dictionary`2 m_lineDict; // 0x68
	private HashSet`1 m_sharedPointSet; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RebuildLines; // 0x10
	private static DelegateBridge __Hotfix0__RefreshAllLineItems; // 0x18
	private static DelegateBridge __Hotfix0__CreateNewLineItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x240979c VA: 0x7594a2179c
	public Void Init(Tools tools) { }
	// RVA: 0x2409820 VA: 0x7594a21820
	public Void Render(SiracusaMapPanelMapViewModel viewModel) { }
	// RVA: 0x24098dc VA: 0x7594a218dc
	private Void _RebuildLines(SiracusaMapPanelMapViewModel viewModel) { }
	// RVA: 0x240a328 VA: 0x7594a22328
	private Void _RefreshAllLineItems(SiracusaMapFocusPolicy policy) { }
	// RVA: 0x240a044 VA: 0x7594a22044
	private LineItem _CreateNewLineItem() { }
	// RVA: 0x240a904 VA: 0x7594a22904
	public Void .ctor() { }
}
```