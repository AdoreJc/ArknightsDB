# ChannelMixer

**Namespace:** `Colorful`


## Fields

- `Vector3 Red`

- `Vector3 Green`

- `Vector3 Blue`

- `Vector3 Constant`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class ChannelMixer : BaseEffect
{
	public Vector3 Red; // 0x28
	public Vector3 Green; // 0x34
	public Vector3 Blue; // 0x40
	public Vector3 Constant; // 0x4c


	// RVA: 0x34e8838 VA: 0x7595b00838
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e89e8 VA: 0x7595b009e8
	protected override String GetShaderName() { }
	// RVA: 0x34e8a28 VA: 0x7595b00a28
	public Void .ctor() { }
}
```