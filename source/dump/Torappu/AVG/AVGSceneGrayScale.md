# AVGSceneGrayScale

**Namespace:** `Torappu.AVG`


## Fields

- `Single m_pendingGrayAmount`

- `Single m_appliedGrayAmount`

- `Single m_pendingInverseAmount`

- `Single m_appliedInverseAmount`

- `Material m_matGrayScale`


## Methods

- `Void _ApplyAmountsToMaterial()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGSceneGrayScale : EffectImplementation
{
	private const Single RED_LUM; // 0x0
	private const Single GREEN_LUM; // 0x0
	private const Single BLUE_LUM; // 0x0
	private Single m_pendingGrayAmount; // 0x24
	private Single m_appliedGrayAmount; // 0x28
	private Single m_pendingInverseAmount; // 0x2c
	private Single m_appliedInverseAmount; // 0x30
	private Material m_matGrayScale; // 0x38


	// RVA: 0x3e9b8c0 VA: 0x75964b38c0
	public override Void GetActiveChannels(List`1 channelList) { }
	// RVA: 0x3e9ba7c VA: 0x75964b3a7c
	public override Single GetAmount(String channel) { }
	// RVA: 0x3e9bb18 VA: 0x75964b3b18
	public override Void Render(CommandBuffer cmd, RenderTargetIdentifier src, RenderTargetIdentifier dst) { }
	// RVA: 0x3e9be00 VA: 0x75964b3e00
	public override Void SetAmount(String channel, Single amount) { }
	// RVA: 0x3e9bca4 VA: 0x75964b3ca4
	private Void _ApplyAmountsToMaterial() { }
	// RVA: 0x3e98d50 VA: 0x75964b0d50
	public Void .ctor() { }
}
```