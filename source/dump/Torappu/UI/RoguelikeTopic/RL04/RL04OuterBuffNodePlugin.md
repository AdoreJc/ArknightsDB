# RL04OuterBuffNodePlugin

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `UIParticle _particleEffectPrefab`

- `Transform _particleEffectHolder`

- `Single _playDelay`

- `Boolean m_cachedActive`

- `Boolean m_instantiated`

- `UIParticle m_particleEffect`

- `Tween m_playTween`


## Methods

- `Void Init(RoguelikeCommonOuterBuffNodeBaseViewModel)`

- `Void Render(String, RoguelikeCommonOuterBuffNodeBaseViewModel)`

- `Void _Play()`

- `Tween _PlayTween()`

- `Void <_PlayTween>b__10_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04OuterBuffNodePlugin : MonoBehaviour, IRoguelikeCommonOuterBuffNodePlugin, IHotfixable
{
	private UIParticle _particleEffectPrefab; // 0x18
	private Transform _particleEffectHolder; // 0x20
	private Single _playDelay; // 0x28
	private Boolean m_cachedActive; // 0x2c
	private Boolean m_instantiated; // 0x2d
	private UIParticle m_particleEffect; // 0x30
	private Tween m_playTween; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__Play; // 0x10
	private static DelegateBridge __Hotfix0__PlayTween; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26efdf4 VA: 0x7594d07df4
	public Void Init(RoguelikeCommonOuterBuffNodeBaseViewModel model) { }
	// RVA: 0x26efe8c VA: 0x7594d07e8c
	public Void Render(String selectedBuffId, RoguelikeCommonOuterBuffNodeBaseViewModel model) { }
	// RVA: 0x26eff50 VA: 0x7594d07f50
	private Void _Play() { }
	// RVA: 0x26f00d4 VA: 0x7594d080d4
	private Tween _PlayTween() { }
	// RVA: 0x26f01d4 VA: 0x7594d081d4
	public Void .ctor() { }
	// RVA: 0x26f0244 VA: 0x7594d08244
	private Void <_PlayTween>b__10_0() { }
}
```