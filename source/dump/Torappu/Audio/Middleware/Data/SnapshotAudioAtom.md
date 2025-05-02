# SnapshotAudioAtom

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `SnapshotBank snapshotBank`

- `Boolean m_listenBegin`

- `Boolean m_poped`


## Methods

- `Void <>xLuaBaseProxy_Stop(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class SnapshotAudioAtom : AudioAtom
{
	public SnapshotBank snapshotBank; // 0x20
	private Boolean m_listenBegin; // 0x28
	private Boolean m_poped; // 0x29
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Stop; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3ee3328 VA: 0x75964fb328
	public override Boolean Update(Single deltaTime) { }
	// RVA: 0x3ee341c VA: 0x75964fb41c
	public override Void Stop(Single fadetime) { }
	// RVA: 0x3ee2f98 VA: 0x75964faf98
	public Void .ctor() { }
	// RVA: 0x3ee34ec VA: 0x75964fb4ec
	private Void <>xLuaBaseProxy_Stop(Single P0) { }
}
```