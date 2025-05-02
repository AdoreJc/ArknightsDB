# StageRankView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean m_isInited`

- `Int32 m_rankCache`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRankView : MonoBehaviour, IHotfixable
{
	private RankPair[] _ranks; // 0x18
	private Boolean m_isInited; // 0x20
	private Int32 m_rankCache; // 0x24
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2fac6ec VA: 0x75955c46ec
	private Void _InitIfNot() { }
	// RVA: 0x2fac760 VA: 0x75955c4760
	public Void Render(Int32 rank) { }
	// RVA: 0x2fac9a4 VA: 0x75955c49a4
	public Void .ctor() { }
}
```