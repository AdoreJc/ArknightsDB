# Act24sideMissionObjView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Text _missionTitle`

- `Text _missionDesc`

- `GameObject _completeBtn`

- `Act24sideMissionStampView _stampView`

- `Act24sideMissionDelegateTitleView _delegateView`

- `Act24sideMissionRewardListView _rewardListView`

- `Boolean m_isCanComplete`

- `String m_missionId`


## Methods

- `Void Render(Act24sideMissionObjViewModel)`

- `Void OnClickCompleteBtn()`

- `Void OnClickDetailBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionObjView : MonoBehaviour, IHotfixable
{
	private Text _missionTitle; // 0x18
	private Text _missionDesc; // 0x20
	private GameObject _completeBtn; // 0x28
	private Act24sideMissionStampView _stampView; // 0x30
	private Act24sideMissionDelegateTitleView _delegateView; // 0x38
	private Act24sideMissionRewardListView _rewardListView; // 0x40
	public Action`1 onClickCompleleBtn; // 0x48
	public Action`1 onClickDetailBtn; // 0x50
	private Boolean m_isCanComplete; // 0x58
	private String m_missionId; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickCompleteBtn; // 0x8
	private static DelegateBridge __Hotfix0_OnClickDetailBtn; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32b7f68 VA: 0x75958cff68
	public Void Render(Act24sideMissionObjViewModel model) { }
	// RVA: 0x32b81e0 VA: 0x75958d01e0
	public Void OnClickCompleteBtn() { }
	// RVA: 0x32b8270 VA: 0x75958d0270
	public Void OnClickDetailBtn() { }
	// RVA: 0x32b82f8 VA: 0x75958d02f8
	public Void .ctor() { }
}
```