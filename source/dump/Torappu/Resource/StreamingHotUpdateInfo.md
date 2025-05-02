# StreamingHotUpdateInfo

**Namespace:** `Torappu.Resource`


## Fields

- `String m_path`

- `HotUpdateInfo m_info`

- `IEnumerator m_preloadRoutine`


## Methods

- `String _Path()`

- `IEnumerator Preload()`

- `Boolean GetOrLoadImmediately(out, out)`

- `IEnumerator _PreloadCoroutine()`

- `IEnumerator _PreloadImpl()`

- `Void _LogStreamingFileError(StreamingResult)`

- `Void _LogDeserializeError(Exception)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class StreamingHotUpdateInfo : Singleton`1
{
	private String m_path; // 0x10
	private HotUpdateInfo m_info; // 0x18
	private IEnumerator m_preloadRoutine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__Path; // 0x8
	private static DelegateBridge __Hotfix0_Preload; // 0x10
	private static DelegateBridge __Hotfix0_GetOrLoadImmediately; // 0x18
	private static DelegateBridge __Hotfix0__PreloadCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__PreloadImpl; // 0x28
	private static DelegateBridge __Hotfix0__LogStreamingFileError; // 0x30
	private static DelegateBridge __Hotfix0__LogDeserializeError; // 0x38


	// RVA: 0x373e40c VA: 0x7595d5640c
	private Void .ctor() { }
	// RVA: 0x373e49c VA: 0x7595d5649c
	private String _Path() { }
	// RVA: 0x373e5a0 VA: 0x7595d565a0
	public IEnumerator Preload() { }
	// RVA: 0x373e674 VA: 0x7595d56674
	public Boolean GetOrLoadImmediately(out HotUpdateInfo info, out Exception error) { }
	// RVA: 0x373eba8 VA: 0x7595d56ba8
	private IEnumerator _PreloadCoroutine() { }
	// RVA: 0x373ec7c VA: 0x7595d56c7c
	private IEnumerator _PreloadImpl() { }
	// RVA: 0x373e988 VA: 0x7595d56988
	private Void _LogStreamingFileError(StreamingResult fileContent) { }
	// RVA: 0x373ea98 VA: 0x7595d56a98
	private Void _LogDeserializeError(Exception e) { }
}
```