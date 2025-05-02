# RL04DifficultyRulesBuffItem

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `Image _icon`

- `Text _buffName`

- `Text _activeTips`


## Methods

- `Void set_buffIconLoader(Func`2)`

- `Void Render(RL04DifficultyRulesBuffModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04DifficultyRulesBuffItem : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Text _buffName; // 0x20
	private Text _activeTips; // 0x28
	private Text[] _descs; // 0x30
	private Func`2 <buffIconLoader>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_buffIconLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_buffIconLoader; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Func`2 buffIconLoader { get; set; }

	// RVA: 0x26ea0a8 VA: 0x7594d020a8
	public Func`2 get_buffIconLoader() { }
	// RVA: 0x26ea110 VA: 0x7594d02110
	public Void set_buffIconLoader(Func`2 value) { }
	// RVA: 0x26ea194 VA: 0x7594d02194
	public Void Render(RL04DifficultyRulesBuffModel model) { }
	// RVA: 0x26ea414 VA: 0x7594d02414
	public Void .ctor() { }
}
```