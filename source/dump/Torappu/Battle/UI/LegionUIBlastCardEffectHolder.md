# LegionUIBlastCardEffectHolder

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _effectToLoad`

- `GameObject m_effect`


## Methods

- `Void PlayBlastEffect()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class LegionUIBlastCardEffectHolder : MonoBehaviour, IHotfixable
{
	private GameObject _effectToLoad; // 0x18
	private GameObject m_effect; // 0x20
	private static DelegateBridge __Hotfix0_PlayBlastEffect; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x203f1b8 VA: 0x75946571b8
	public Void PlayBlastEffect() { }
	// RVA: 0x203f288 VA: 0x7594657288
	private Void _InitIfNot() { }
	// RVA: 0x203f480 VA: 0x7594657480
	public Void .ctor() { }
}
```