# ActMultiV3PhotoCharViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 slotIdx`

- `String skinId`

- `Boolean isValidChar`

- `Vector3 translation`

- `Quaternion rotation`

- `Vector3 scale`

- `String animName`

- `String defaultAnimName`

- `Int32 frame`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoCharViewModel : IHotfixable
{
	public Int32 slotIdx; // 0x10
	public String skinId; // 0x18
	public Boolean isValidChar; // 0x20
	public Vector3 translation; // 0x24
	public Quaternion rotation; // 0x30
	public Vector3 scale; // 0x40
	public String animName; // 0x50
	public String defaultAnimName; // 0x58
	public Int32 frame; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x31201c0 VA: 0x75957381c0
	public Void .ctor(PhotoCharInfo charInfo, List`1 slots, String defaultAct) { }
}
```