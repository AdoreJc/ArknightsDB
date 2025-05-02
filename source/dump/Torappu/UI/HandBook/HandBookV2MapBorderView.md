# HandBookV2MapBorderView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapBorderItemView _itemTemplate`

- `Transform _itemContainer`

- `HandBookV2ForceViewModel m_forceViewModel`


## Methods

- `Void Render(HandBookV2ForceViewModel, Dictionary`2)`

- `Void _RenderBorders(HandBookV2PointData, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapBorderView : MonoBehaviour, IHotfixable
{
	private HandBookV2MapBorderItemView _itemTemplate; // 0x18
	private Transform _itemContainer; // 0x20
	private Dictionary`2 m_pointIdx2BorderItemMap; // 0x28
	private Dictionary`2 m_pointIdx2ForceIdMap; // 0x30
	private HandBookV2ForceViewModel m_forceViewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderBorders; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ed098c VA: 0x75954e898c
	public Void Render(HandBookV2ForceViewModel viewModel, Dictionary`2 pointIndex2ForceIdMap) { }
	// RVA: 0x2ed0ac4 VA: 0x75954e8ac4
	private Void _RenderBorders(HandBookV2PointData pointData, Boolean isForceUnlock) { }
	// RVA: 0x2ed0c58 VA: 0x75954e8c58
	public Void .ctor() { }
}
```