# UIBattleStartPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIStageInfo _stageInfo`

- `UIAnimationPerform _perform`

- `Action m_finishCb`


## Methods

- `Void Show(Action)`

- `Void _OnComplete(Boolean)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleStartPanel : MonoBehaviour
{
	private UIStageInfo _stageInfo; // 0x18
	private UIAnimationPerform _perform; // 0x20
	private Action m_finishCb; // 0x28


	// RVA: 0x2046afc VA: 0x759465eafc
	public Void Show(Action finishCb) { }
	// RVA: 0x2046bbc VA: 0x759465ebbc
	private Void _OnComplete(Boolean completed) { }
	// RVA: 0x2046c14 VA: 0x759465ec14
	private Void Start() { }
	// RVA: 0x2046cc8 VA: 0x759465ecc8
	public Void .ctor() { }
}
```