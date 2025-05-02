# AsyncResource

**Namespace:** `Torappu.Resource`


## Fields

- `Object m_asset`

- `ResourceRequest m_resRequest`

- `AssetBundleRequest m_abRequest`

- `Boolean m_isLoaded`


## Properties

- `Boolean isDone`


## Methods

- `Boolean get_isDone()`

- `ResourceRequest GetResourceRequest()`

- `AssetBundleRequest GetAssetBundleRequest()`

- `Void AddLoadedCallback(Action`1)`

- `T GetAsset()`

- `TComp GetComponent()`

- `Void _OnLoadFinished()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Resource
public class AsyncResource : CustomYieldInstruction
{
	private Action`1 m_onLoaded; // 0x10
	private Object m_asset; // 0x18
	private ResourceRequest m_resRequest; // 0x20
	private AssetBundleRequest m_abRequest; // 0x28
	private Boolean m_isLoaded; // 0x30

	public override Boolean keepWaiting { get; }
	public Boolean isDone { get; }

	// RVA: 0x6798008 VA: 0x7598db0008
	public override Boolean get_keepWaiting() { }
	// RVA: 0x67980bc VA: 0x7598db00bc
	public Boolean get_isDone() { }
	// RVA: 0x67980dc VA: 0x7598db00dc
	public Void .ctor(ResourceRequest resRequest) { }
	// RVA: 0x679810c VA: 0x7598db010c
	public Void .ctor(AssetBundleRequest abRequest) { }
	// RVA: 0x6793688 VA: 0x7598dab688
	public Void .ctor(Object asset) { }
	// RVA: 0x679813c VA: 0x7598db013c
	public ResourceRequest GetResourceRequest() { }
	// RVA: 0x6798144 VA: 0x7598db0144
	public AssetBundleRequest GetAssetBundleRequest() { }
	// RVA: 0x67935a0 VA: 0x7598dab5a0
	public Void AddLoadedCallback(Action`1 onLoaded) { }
	// RVA: 0x679814c VA: 0x7598db014c
	public virtual Object GetAsset() { }
	// RVA: 0x VA: 0x0
	public T GetAsset() { }
	// RVA: 0x VA: 0x0
	public TComp GetComponent() { }
	// RVA: 0x6798048 VA: 0x7598db0048
	private Void _OnLoadFinished() { }
}
```