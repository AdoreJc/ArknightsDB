# SixStarGroupRewardView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SimpleLayoutContent _content`

- `UIStateFinder m_stateFinder`

- `String m_cachedSelectStateId`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void Render(List`1, String)`

- `Void EventOnBackBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarGroupRewardView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private UIStateFinder m_stateFinder; // 0x20
	private List`1 m_cachedStageModelList; // 0x30
	private String m_cachedSelectStateId; // 0x38
	private Adapter m_adapter; // 0x40
	private Boolean m_hasInited; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f48b38 VA: 0x7595560b38
	public Void Render(List`1 modelList, String selectStageId) { }
	// RVA: 0x2f493e8 VA: 0x75955613e8
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x2f49318 VA: 0x7595561318
	private Void _InitIfNot() { }
	// RVA: 0x2f49520 VA: 0x7595561520
	public Void .ctor() { }
}
```