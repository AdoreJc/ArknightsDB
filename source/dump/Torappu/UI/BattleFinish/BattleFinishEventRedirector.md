# BattleFinishEventRedirector

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Component _receiver`


## Methods

- `Void UpLevel()`

- `Void _SendMessageToReceiver(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishEventRedirector : MonoBehaviour
{
	public const Int32 EVT_LEVEL_UP; // 0x0
	private Component _receiver; // 0x18


	// RVA: 0x2e8e5cc VA: 0x75954a65cc
	public Void UpLevel() { }
	// RVA: 0x2e8e5d0 VA: 0x75954a65d0
	private Void _SendMessageToReceiver(Int32 msg) { }
	// RVA: 0x2e8e6cc VA: 0x75954a66cc
	public Void .ctor() { }
}
```