# Act5D1StageEntryButtonObj

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Image _backImage`

- `Image _icon`

- `Text _stageName`

- `Text _groupName`

- `GameObject _remainTime`

- `Text _remainText`

- `UIStringEvent _onClick`

- `String m_cacheStageId`


## Methods

- `Void RenderStage(String, RuneRecurrentStateData)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1StageEntryButtonObj : MonoBehaviour, IHotfixable
{
	private Image _backImage; // 0x18
	private Image _icon; // 0x20
	private Text _stageName; // 0x28
	private Text _groupName; // 0x30
	private GameObject _remainTime; // 0x38
	private Text _remainText; // 0x40
	private UIStringEvent _onClick; // 0x48
	private String m_cacheStageId; // 0x50
	private static DelegateBridge __Hotfix0_RenderStage; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31c84f4 VA: 0x75957e04f4
	public Void RenderStage(String stageId, RuneRecurrentStateData recurrentData) { }
	// RVA: 0x31c890c VA: 0x75957e090c
	public Void OnClick() { }
	// RVA: 0x31c89a0 VA: 0x75957e09a0
	public Void .ctor() { }
}
```