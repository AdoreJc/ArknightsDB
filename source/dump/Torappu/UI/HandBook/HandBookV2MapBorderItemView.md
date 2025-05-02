# HandBookV2MapBorderItemView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String m_forceId`


## Methods

- `Void Render(Dictionary`2, String, HandBookV2PointData, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapBorderItemView : MonoBehaviour, IHotfixable
{
	private Image[] _lineList; // 0x18
	private Dictionary`2 m_pointIdx2ForceIdMap; // 0x20
	private String m_forceId; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ed0670 VA: 0x75954e8670
	public Void Render(Dictionary`2 pointIdx2ForceIdMap, String forceId, HandBookV2PointData pointData, String color, Boolean isForceUnlock) { }
	// RVA: 0x2ed091c VA: 0x75954e891c
	public Void .ctor() { }
}
```