# Act24sideMissionView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMissionLoopAdapter _loopAdapter`

- `Text _missionNum`

- `GameObject _bottomBar`

- `LoopVerticalScrollRect _scrollRect`

- `Boolean m_isInited`

- `Act24sideMissionViewModel m_model`

- `Single m_cachedSequenceNum`

- `Action onClickOneClickBtn`


## Methods

- `Void OnClickOneClickBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionView : DataBinder`1
{
	private Act24sideMissionLoopAdapter _loopAdapter; // 0x20
	private Text _missionNum; // 0x28
	private GameObject _bottomBar; // 0x30
	private LoopVerticalScrollRect _scrollRect; // 0x38
	private Boolean m_isInited; // 0x40
	private Act24sideMissionViewModel m_model; // 0x48
	private Single m_cachedSequenceNum; // 0x50
	public Action`1 onClickDetailBtn; // 0x58
	public Action`1 onClickCompleteBtn; // 0x60
	public Action onClickOneClickBtn; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnClickOneClickBtn; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32bf110 VA: 0x75958d7110
	public override Void OnValueChanged(Act24sideMissionProp property) { }
	// RVA: 0x32bf2f8 VA: 0x75958d72f8
	public Void OnClickOneClickBtn() { }
	// RVA: 0x32bf37c VA: 0x75958d737c
	public Void .ctor() { }
}
```