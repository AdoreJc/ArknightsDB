# UILegionDangerLevelEffectHolder

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _effectUpgradeLoad`

- `ParticleSystem m_effectUpgrade`

- `Int32 m_nextStep`

- `Int32 m_lastlevel`

- `GameObject m_lastSetpEffect`

- `Boolean m_isMaxStep`


## Methods

- `Void UpdateLevelEffect(Int32)`

- `Void InitEffect(Int32)`

- `Void _PlayUpgradeEffect(Int32)`

- `Void _ChangeStepEffect(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILegionDangerLevelEffectHolder : MonoBehaviour, IHotfixable
{
	private GameObject _effectUpgradeLoad; // 0x18
	private List`1 _stepEffects; // 0x20
	private ParticleSystem m_effectUpgrade; // 0x28
	private List`1 m_stepEffectInsts; // 0x30
	private Int32 m_nextStep; // 0x38
	private Int32 m_lastlevel; // 0x3c
	private GameObject m_lastSetpEffect; // 0x40
	private Boolean m_isMaxStep; // 0x48
	private static DelegateBridge __Hotfix0_UpdateLevelEffect; // 0x0
	private static DelegateBridge __Hotfix0_InitEffect; // 0x8
	private static DelegateBridge __Hotfix0__PlayUpgradeEffect; // 0x10
	private static DelegateBridge __Hotfix0__ChangeStepEffect; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2080aa0 VA: 0x7594698aa0
	public Void UpdateLevelEffect(Int32 level) { }
	// RVA: 0x2080848 VA: 0x7594698848
	public Void InitEffect(Int32 initLevel) { }
	// RVA: 0x2080b9c VA: 0x7594698b9c
	private Void _PlayUpgradeEffect(Int32 level) { }
	// RVA: 0x2080cd8 VA: 0x7594698cd8
	private Void _ChangeStepEffect(Int32 level) { }
	// RVA: 0x2080eb0 VA: 0x7594698eb0
	private Void _InitIfNot() { }
	// RVA: 0x208133c VA: 0x759469933c
	public Void .ctor() { }
}
```