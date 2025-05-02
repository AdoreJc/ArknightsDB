# ChannelSwapper

**Namespace:** `Colorful`


## Fields

- `Channel RedSource`

- `Channel GreenSource`

- `Channel BlueSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class ChannelSwapper : BaseEffect
{
	public Channel RedSource; // 0x28
	public Channel GreenSource; // 0x2c
	public Channel BlueSource; // 0x30
	private static Vector4[] m_Channels; // 0x0


	// RVA: 0x34e8a44 VA: 0x7595b00a44
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e8c04 VA: 0x7595b00c04
	protected override String GetShaderName() { }
	// RVA: 0x34e8c44 VA: 0x7595b00c44
	public Void .ctor() { }
	// RVA: 0x34e8c58 VA: 0x7595b00c58
	private static Void .cctor() { }
}
```