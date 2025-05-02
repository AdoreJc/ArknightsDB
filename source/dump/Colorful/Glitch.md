# Glitch

**Namespace:** `Colorful`


## Fields

- `Boolean RandomActivation`

- `Vector2 RandomEvery`

- `Vector2 RandomDuration`

- `GlitchingMode Mode`

- `InterferenceSettings SettingsInterferences`

- `TearingSettings SettingsTearing`

- `Boolean m_Activated`

- `Single m_EveryTimer`

- `Single m_EveryTimerEnd`

- `Single m_DurationTimer`

- `Single m_DurationTimerEnd`


## Properties

- `Boolean IsActive`


## Methods

- `Boolean get_IsActive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Glitch : BaseEffect
{
	public Boolean RandomActivation; // 0x28
	public Vector2 RandomEvery; // 0x2c
	public Vector2 RandomDuration; // 0x34
	public GlitchingMode Mode; // 0x3c
	public InterferenceSettings SettingsInterferences; // 0x40
	public TearingSettings SettingsTearing; // 0x48
	protected Boolean m_Activated; // 0x50
	protected Single m_EveryTimer; // 0x54
	protected Single m_EveryTimerEnd; // 0x58
	protected Single m_DurationTimer; // 0x5c
	protected Single m_DurationTimerEnd; // 0x60

	public Boolean IsActive { get; }

	// RVA: 0x34eae20 VA: 0x7595b02e20
	public Boolean get_IsActive() { }
	// RVA: 0x34eae28 VA: 0x7595b02e28
	protected override Void Start() { }
	// RVA: 0x34eae4c VA: 0x7595b02e4c
	protected virtual Void Update() { }
	// RVA: 0x34eaeec VA: 0x7595b02eec
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eb044 VA: 0x7595b03044
	protected virtual Void DoInterferences(RenderTexture source, RenderTexture destination, InterferenceSettings settings) { }
	// RVA: 0x34eb10c VA: 0x7595b0310c
	protected virtual Void DoTearing(RenderTexture source, RenderTexture destination, TearingSettings settings) { }
	// RVA: 0x34eb1fc VA: 0x7595b031fc
	protected override String GetShaderName() { }
	// RVA: 0x34eb23c VA: 0x7595b0323c
	public Void .ctor() { }
}
```