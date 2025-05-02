# RL03DifficultyRulesBuffItem

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Image _icon`

- `Text _buffName`

- `Text _activeTips`

- `Text _desc`


## Methods

- `Void set_buffIconLoader(Func`2)`

- `Void Render(RL03DifficultyRulesBuffModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03DifficultyRulesBuffItem : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Text _buffName; // 0x20
	private Text _activeTips; // 0x28
	private Text _desc; // 0x30
	private Func`2 <buffIconLoader>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_buffIconLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_buffIconLoader; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Func`2 buffIconLoader { get; set; }

	// RVA: 0x26a0b8c VA: 0x7594cb8b8c
	public Func`2 get_buffIconLoader() { }
	// RVA: 0x26a0bf4 VA: 0x7594cb8bf4
	public Void set_buffIconLoader(Func`2 value) { }
	// RVA: 0x26a0c78 VA: 0x7594cb8c78
	public Void Render(RL03DifficultyRulesBuffModel model) { }
	// RVA: 0x26a0f90 VA: 0x7594cb8f90
	public Void .ctor() { }
}
```