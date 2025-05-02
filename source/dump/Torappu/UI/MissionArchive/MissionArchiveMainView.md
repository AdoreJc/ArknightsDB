# MissionArchiveMainView

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `GameObject _hiddenPanel`

- `Boolean m_hasInited`

- `Action <playHiddenClipsEvent>k__BackingField`


## Properties

- `Action playHiddenClipsEvent`


## Methods

- `Void set_nodeSelectEvent(Action`1)`

- `Action get_playHiddenClipsEvent()`

- `Void set_playHiddenClipsEvent(Action)`

- `Void OnPlayHiddenClipsEvent()`

- `Tween PlayNodeSelect(String)`

- `Void ResetNodeSelect()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchiveMainView : DataBinder`1
{
	private List`1 _nodeViews; // 0x20
	private GameObject _hiddenPanel; // 0x28
	private Boolean m_hasInited; // 0x30
	private Action`1 <nodeSelectEvent>k__BackingField; // 0x38
	private Action <playHiddenClipsEvent>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_nodeSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_nodeSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_playHiddenClipsEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_playHiddenClipsEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnPlayHiddenClipsEvent; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_PlayNodeSelect; // 0x30
	private static DelegateBridge __Hotfix0_ResetNodeSelect; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 nodeSelectEvent { get; set; }
	private Action playHiddenClipsEvent { get; set; }

	// RVA: 0x272b82c VA: 0x7594d4382c
	private Action`1 get_nodeSelectEvent() { }
	// RVA: 0x2728128 VA: 0x7594d40128
	public Void set_nodeSelectEvent(Action`1 value) { }
	// RVA: 0x272b894 VA: 0x7594d43894
	private Action get_playHiddenClipsEvent() { }
	// RVA: 0x27281ac VA: 0x7594d401ac
	public Void set_playHiddenClipsEvent(Action value) { }
	// RVA: 0x272b8fc VA: 0x7594d438fc
	public Void OnPlayHiddenClipsEvent() { }
	// RVA: 0x272b998 VA: 0x7594d43998
	public override Void OnValueChanged(MissionArchiveViewProperty property) { }
	// RVA: 0x272a788 VA: 0x7594d42788
	public Tween PlayNodeSelect(String nodeId) { }
	// RVA: 0x27289f4 VA: 0x7594d409f4
	public Void ResetNodeSelect() { }
	// RVA: 0x272bb20 VA: 0x7594d43b20
	private Void _InitIfNot() { }
	// RVA: 0x272c0e4 VA: 0x7594d440e4
	public Void .ctor() { }
}
```