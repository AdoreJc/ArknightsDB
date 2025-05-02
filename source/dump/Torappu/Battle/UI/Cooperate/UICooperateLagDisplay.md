# UICooperateLagDisplay

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Image _background`

- `Text _lagText`

- `Int32 m_preLag`


## Methods

- `Void UpdateData(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateLagDisplay : MonoBehaviour, IHotfixable
{
	private LagStatus[] _statusLevels; // 0x18
	private Image _background; // 0x20
	private Text _lagText; // 0x28
	private Int32 m_preLag; // 0x30
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x20e85cc VA: 0x75947005cc
	public Void UpdateData(Int32 lag) { }
	// RVA: 0x20e93c4 VA: 0x75947013c4
	public Void .ctor() { }
}
```