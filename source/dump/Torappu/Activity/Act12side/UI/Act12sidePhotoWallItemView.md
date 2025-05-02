# Act12sidePhotoWallItemView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `String _photoId`

- `Text _textUnlockCount`

- `TwoStateToggle _stateToggle`

- `GameObject _trackPointGo`

- `Boolean m_hasInited`

- `String m_actId`

- `PhotoInfo m_photoData`

- `MileStoneInfo m_milestoneData`


## Methods

- `Void set_onClickAction(Action`1)`

- `Void UpdateState(String)`

- `Void OnPhotoClick()`

- `Void OnLockClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sidePhotoWallItemView : MonoBehaviour, IHotfixable
{
	private String _photoId; // 0x18
	private Text _textUnlockCount; // 0x20
	private TwoStateToggle _stateToggle; // 0x28
	private GameObject _trackPointGo; // 0x30
	private Action`1 <onClickAction>k__BackingField; // 0x38
	private Boolean m_hasInited; // 0x40
	private String m_actId; // 0x48
	private PhotoInfo m_photoData; // 0x50
	private MileStoneInfo m_milestoneData; // 0x58
	private static DelegateBridge __Hotfix0_get_onClickAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickAction; // 0x8
	private static DelegateBridge __Hotfix0_UpdateState; // 0x10
	private static DelegateBridge __Hotfix0_OnPhotoClick; // 0x18
	private static DelegateBridge __Hotfix0_OnLockClick; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onClickAction { get; set; }

	// RVA: 0x3467d40 VA: 0x7595a7fd40
	private Action`1 get_onClickAction() { }
	// RVA: 0x34663e8 VA: 0x7595a7e3e8
	public Void set_onClickAction(Action`1 value) { }
	// RVA: 0x3466270 VA: 0x7595a7e270
	public Void UpdateState(String actId) { }
	// RVA: 0x3467fcc VA: 0x7595a7ffcc
	public Void OnPhotoClick() { }
	// RVA: 0x3468074 VA: 0x7595a80074
	public Void OnLockClick() { }
	// RVA: 0x3467da8 VA: 0x7595a7fda8
	private Void _InitIfNot() { }
	// RVA: 0x3468170 VA: 0x7595a80170
	public Void .ctor() { }
}
```