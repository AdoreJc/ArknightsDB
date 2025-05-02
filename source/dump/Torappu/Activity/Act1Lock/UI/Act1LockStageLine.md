# Act1LockStageLine

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Image _lineImg`

- `String _stageId`


## Properties

- `String stageId`


## Methods

- `String get_stageId()`

- `Void RenderLine(Boolean, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockStageLine : MonoBehaviour, IHotfixable
{
	private Image _lineImg; // 0x18
	private String _stageId; // 0x20
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_RenderLine; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String stageId { get; }

	// RVA: 0x33cf5a8 VA: 0x75959e75a8
	public String get_stageId() { }
	// RVA: 0x33cf610 VA: 0x75959e7610
	public Void RenderLine(Boolean stageUnlocked, Color color) { }
	// RVA: 0x33d466c VA: 0x75959ec66c
	public Void .ctor() { }
}
```