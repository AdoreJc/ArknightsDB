# AVGSceneFocusOut

**Namespace:** `Torappu.AVG`


## Fields

- `PostDisplayGroup m_displayGroup`

- `Material m_blurMat0`


## Methods

- `Boolean TryRegister(PostDisplayItem)`

- `Void BeforeItemDisposed(PostDisplayItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGSceneFocusOut : EffectImplementation, IProcessor
{
	private const Single BLUR_SIZE; // 0x0
	private PostDisplayGroup m_displayGroup; // 0x28
	private Dictionary`2 m_amounts; // 0x30
	private Material m_blurMat0; // 0x38


	// RVA: 0x3e9af38 VA: 0x75964b2f38
	public override Void GetActiveChannels(List`1 channelList) { }
	// RVA: 0x3e9b190 VA: 0x75964b3190
	public override Single GetAmount(String channel) { }
	// RVA: 0x3e9b20c VA: 0x75964b320c
	public override Void Render(CommandBuffer cmd, RenderTargetIdentifier src, RenderTargetIdentifier dst) { }
	// RVA: 0x3e9b584 VA: 0x75964b3584
	public override Void SetAmount(String channel, Single amount) { }
	// RVA: 0x3e9b744 VA: 0x75964b3744
	public override Void Dispose() { }
	// RVA: 0x3e9b5f0 VA: 0x75964b35f0
	private SetWhenBind`2 _EnsureAmountSetter(String channel) { }
	// RVA: 0x3e9b768 VA: 0x75964b3768
	private static Void _SetAmountFunc(BaseItem item, Single amount) { }
	// RVA: 0x3e9b778 VA: 0x75964b3778
	public Boolean TryRegister(PostDisplayItem item) { }
	// RVA: 0x3e9b844 VA: 0x75964b3844
	public Void BeforeItemDisposed(PostDisplayItem item) { }
	// RVA: 0x3e98cc8 VA: 0x75964b0cc8
	public Void .ctor() { }
}
```