# HandBookAvgView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Text _detailText`

- `Text _titleText`

- `HandbookAvgData m_cacheData`

- `String m_cacheCharId`


## Methods

- `Void set_onClick(Action`1)`

- `Void RenderView(Int32, Int32, HandbookAvgData, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookAvgView : MonoBehaviour, IHotfixable
{
	private Text _detailText; // 0x18
	private Text _titleText; // 0x20
	private HandbookAvgData m_cacheData; // 0x28
	private String m_cacheCharId; // 0x30
	private Action`1 <onClick>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClick { get; set; }

	// RVA: 0x2ea99bc VA: 0x75954c19bc
	private Action`1 get_onClick() { }
	// RVA: 0x2ea971c VA: 0x75954c171c
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2ea97a0 VA: 0x75954c17a0
	public Void RenderView(Int32 currentCount, Int32 totalCount, HandbookAvgData data, String charId) { }
	// RVA: 0x2ea9a24 VA: 0x75954c1a24
	public Void OnClick() { }
	// RVA: 0x2ea9ad4 VA: 0x75954c1ad4
	public Void .ctor() { }
}
```