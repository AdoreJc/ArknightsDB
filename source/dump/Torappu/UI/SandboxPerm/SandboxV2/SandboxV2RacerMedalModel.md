# SandboxV2RacerMedalModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String name`

- `String desc`

- `String iconId`

- `String smallIconId`

- `String topicId`

- `Int32 m_sortId`

- `String m_medalId`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerMedalModel : IHotfixable, IComparable
{
	public String name; // 0x10
	public String desc; // 0x18
	public String iconId; // 0x20
	public String smallIconId; // 0x28
	public String topicId; // 0x30
	private Int32 m_sortId; // 0x38
	private String m_medalId; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8


	// RVA: 0x25e628c VA: 0x7594bfe28c
	public Void .ctor(String topicId, SandboxV2RacerMedalInfo medalInfo) { }
	// RVA: 0x25e6388 VA: 0x7594bfe388
	public Int32 CompareTo(Object obj) { }
}
```