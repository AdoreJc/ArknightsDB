# FifthAnnivExploreEventInfoItemView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _textTypeName`

- `Text _textName`

- `UIAtlasObject _iconAtlas`

- `UIAtlasImage _imgIcon`

- `UIStateFinder m_stateFinder`

- `String m_planId`


## Methods

- `Void Render(Int32, FifthAnnivExplorePlanModel)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreEventInfoItemView : MonoBehaviour, IHotfixable
{
	private Text _textTypeName; // 0x18
	private Text _textName; // 0x20
	private UIAtlasObject _iconAtlas; // 0x28
	private UIAtlasImage _imgIcon; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private String m_planId; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2913238 VA: 0x7594f2b238
	public Void Render(Int32 position, FifthAnnivExplorePlanModel planModel) { }
	// RVA: 0x29133ec VA: 0x7594f2b3ec
	public Void EventOnItemClick() { }
	// RVA: 0x29134ec VA: 0x7594f2b4ec
	public Void .ctor() { }
}
```