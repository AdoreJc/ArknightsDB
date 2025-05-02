# ActMultiV3TitleViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `String titleId`

- `Int32 order`

- `String titleDesc`

- `Boolean isBack`

- `Boolean isUnlocked`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TitleViewModel : IHotfixable
{
	public String actId; // 0x10
	public String titleId; // 0x18
	public Int32 order; // 0x20
	public String titleDesc; // 0x28
	public Boolean isBack; // 0x30
	public Boolean isUnlocked; // 0x31
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x3120a74 VA: 0x7595738a74
	public Void .ctor(String actId, String titleId, ActMultiV3TitleData titleData) { }
}
```