# MeetingPeerAdapter

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _peerProto`

- `Transform _poolTransform`

- `Single _avatarScale`

- `IMeetingSession <session>k__BackingField`


## Properties

- `IMeetingSession session`


## Methods

- `IMeetingSession get_session()`

- `Void set_session(IMeetingSession)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingPeerAdapter : LoopScrollAdapter`2
{
	private GameObject _peerProto; // 0x58
	private Transform _poolTransform; // 0x60
	private Single _avatarScale; // 0x68
	private IMeetingSession <session>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_session; // 0x0
	private static DelegateBridge __Hotfix0_set_session; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public IMeetingSession session { get; set; }

	// RVA: 0x3dfd384 VA: 0x7596415384
	public IMeetingSession get_session() { }
	// RVA: 0x3dfd3ec VA: 0x75964153ec
	public Void set_session(IMeetingSession value) { }
	// RVA: 0x3dfd470 VA: 0x7596415470
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3dfd540 VA: 0x7596415540
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, IPeer data) { }
	// RVA: 0x3dfdc1c VA: 0x7596415c1c
	public Void .ctor() { }
}
```