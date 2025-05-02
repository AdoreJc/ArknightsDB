# CarvingMainChallengeInfoRoundItemView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Text _roundItemTitle`

- `SimpleLayoutContent _materialContent`

- `Single _materialScale`

- `Boolean m_isInited`

- `MaterialItemAdapter m_adapter`


## Methods

- `Void Render(CarvingMainChallengeInfoRoundItemViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeInfoRoundItemView : MonoBehaviour, IHotfixable
{
	private Text _roundItemTitle; // 0x18
	private SimpleLayoutContent _materialContent; // 0x20
	private Single _materialScale; // 0x28
	private Boolean m_isInited; // 0x2c
	private MaterialItemAdapter m_adapter; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2dab280 VA: 0x75953c3280
	public Void Render(CarvingMainChallengeInfoRoundItemViewModel model) { }
	// RVA: 0x2dab408 VA: 0x75953c3408
	private Void _InitIfNot() { }
	// RVA: 0x2dab644 VA: 0x75953c3644
	public Void .ctor() { }
}
```