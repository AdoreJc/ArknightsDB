# SnapshotBank

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `Bank targetFxBank`

- `String targetSnapshot`

- `String hookSoundFxBank`

- `Single delay`

- `Single duration`


## Methods

- `Void PopAtom()`

- `Boolean _InitTargetBank()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class SnapshotBank : Bank
{
	private static List`1 s_activeSnapshotBank; // 0x0
	public Bank targetFxBank; // 0x30
	public String targetSnapshot; // 0x38
	public String hookSoundFxBank; // 0x40
	public Single delay; // 0x48
	public Single duration; // 0x4c
	private static DelegateBridge __Hotfix0_Play; // 0x8
	private static DelegateBridge __Hotfix0_PopAtom; // 0x10
	private static DelegateBridge __Hotfix0_TriggerSnapshot; // 0x18
	private static DelegateBridge __Hotfix0_ReverseSnapshot; // 0x20
	private static DelegateBridge __Hotfix0__InitTargetBank; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3ee2aa8 VA: 0x75964faaa8
	public override AudioAtom Play(Vector3 position) { }
	// RVA: 0x3ee3004 VA: 0x75964fb004
	public Void PopAtom() { }
	// RVA: 0x3ee2df4 VA: 0x75964fadf4
	public static Void TriggerSnapshot(SnapshotBank bank) { }
	// RVA: 0x3ee30bc VA: 0x75964fb0bc
	public static Void ReverseSnapshot(SnapshotBank deadBank) { }
	// RVA: 0x3ee2c70 VA: 0x75964fac70
	private Boolean _InitTargetBank() { }
	// RVA: 0x3ee3208 VA: 0x75964fb208
	public Void .ctor() { }
	// RVA: 0x3ee3290 VA: 0x75964fb290
	private static Void .cctor() { }
}
```