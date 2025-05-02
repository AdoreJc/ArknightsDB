# RoguelikeClassicEndingSeedView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIAnimationLocation _seedEntryAnim`

- `Text _seedText`

- `Tween m_entryTween`

- `Boolean m_hasPlayedEntryAnim`

- `Action onCopySeed`


## Methods

- `Void DoRender(RoguelikeEndingControllerBase, RoguelikeClassicEndingViewModel)`

- `IEnumerator _ApplyInAnim()`

- `Void OnCopySeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingSeedView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _seedEntryAnim; // 0x18
	private Text _seedText; // 0x28
	private Tween m_entryTween; // 0x30
	private Boolean m_hasPlayedEntryAnim; // 0x38
	public Action onCopySeed; // 0x40
	private static DelegateBridge __Hotfix0_DoRender; // 0x0
	private static DelegateBridge __Hotfix0__ApplyInAnim; // 0x8
	private static DelegateBridge __Hotfix0_OnCopySeed; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a24238 VA: 0x759503c238
	public Void DoRender(RoguelikeEndingControllerBase controller, RoguelikeClassicEndingViewModel endingViewModel) { }
	// RVA: 0x2a2c360 VA: 0x7595044360
	private IEnumerator _ApplyInAnim() { }
	// RVA: 0x2a2c434 VA: 0x7595044434
	public Void OnCopySeed() { }
	// RVA: 0x2a2c4b8 VA: 0x75950444b8
	public Void .ctor() { }
}
```