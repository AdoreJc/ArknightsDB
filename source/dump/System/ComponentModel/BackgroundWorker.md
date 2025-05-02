# BackgroundWorker

**Namespace:** `System.ComponentModel`


## Fields

- `Boolean _canCancelWorker`

- `Boolean _workerReportsProgress`

- `Boolean _cancellationPending`

- `Boolean _isRunning`

- `AsyncOperation _asyncOperation`

- `DoWorkEventHandler DoWork`

- `ProgressChangedEventHandler ProgressChanged`

- `RunWorkerCompletedEventHandler RunWorkerCompleted`


## Properties

- `Boolean CancellationPending`

- `Boolean IsBusy`

- `Boolean WorkerReportsProgress`

- `Boolean WorkerSupportsCancellation`


## Methods

- `Void AsyncOperationCompleted(Object)`

- `Boolean get_CancellationPending()`

- `Void CancelAsync()`

- `Void add_DoWork(DoWorkEventHandler)`

- `Void remove_DoWork(DoWorkEventHandler)`

- `Boolean get_IsBusy()`

- `Void add_ProgressChanged(ProgressChangedEventHandler)`

- `Void remove_ProgressChanged(ProgressChangedEventHandler)`

- `Void ProgressReporter(Object)`

- `Void ReportProgress(Int32)`

- `Void ReportProgress(Int32, Object)`

- `Void RunWorkerAsync()`

- `Void RunWorkerAsync(Object)`

- `Void add_RunWorkerCompleted(RunWorkerCompletedEventHandler)`

- `Void remove_RunWorkerCompleted(RunWorkerCompletedEventHandler)`

- `Boolean get_WorkerReportsProgress()`

- `Void set_WorkerReportsProgress(Boolean)`

- `Boolean get_WorkerSupportsCancellation()`

- `Void set_WorkerSupportsCancellation(Boolean)`

- `Void WorkerThreadStart(Object)`

- `Void <RunWorkerAsync>b__27_0(Object)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class BackgroundWorker : Component
{
	private Boolean _canCancelWorker; // 0x28
	private Boolean _workerReportsProgress; // 0x29
	private Boolean _cancellationPending; // 0x2a
	private Boolean _isRunning; // 0x2b
	private AsyncOperation _asyncOperation; // 0x30
	private readonly SendOrPostCallback _operationCompleted; // 0x38
	private readonly SendOrPostCallback _progressReporter; // 0x40
	private DoWorkEventHandler DoWork; // 0x48
	private ProgressChangedEventHandler ProgressChanged; // 0x50
	private RunWorkerCompletedEventHandler RunWorkerCompleted; // 0x58

	public Boolean CancellationPending { get; }
	public Boolean IsBusy { get; }
	public Boolean WorkerReportsProgress { get; set; }
	public Boolean WorkerSupportsCancellation { get; set; }

	// RVA: 0x63b06a4 VA: 0x75989c86a4
	public Void .ctor() { }
	// RVA: 0x63b079c VA: 0x75989c879c
	private Void AsyncOperationCompleted(Object arg) { }
	// RVA: 0x63b0830 VA: 0x75989c8830
	public Boolean get_CancellationPending() { }
	// RVA: 0x63b0838 VA: 0x75989c8838
	public Void CancelAsync() { }
	// RVA: 0x63b08a0 VA: 0x75989c88a0
	public Void add_DoWork(DoWorkEventHandler value) { }
	// RVA: 0x63b093c VA: 0x75989c893c
	public Void remove_DoWork(DoWorkEventHandler value) { }
	// RVA: 0x63b09d8 VA: 0x75989c89d8
	public Boolean get_IsBusy() { }
	// RVA: 0x63b09e0 VA: 0x75989c89e0
	protected virtual Void OnDoWork(DoWorkEventArgs e) { }
	// RVA: 0x63b0a08 VA: 0x75989c8a08
	protected virtual Void OnRunWorkerCompleted(RunWorkerCompletedEventArgs e) { }
	// RVA: 0x63b0a30 VA: 0x75989c8a30
	protected virtual Void OnProgressChanged(ProgressChangedEventArgs e) { }
	// RVA: 0x63b0a58 VA: 0x75989c8a58
	public Void add_ProgressChanged(ProgressChangedEventHandler value) { }
	// RVA: 0x63b0af4 VA: 0x75989c8af4
	public Void remove_ProgressChanged(ProgressChangedEventHandler value) { }
	// RVA: 0x63b0b90 VA: 0x75989c8b90
	private Void ProgressReporter(Object arg) { }
	// RVA: 0x63b0c20 VA: 0x75989c8c20
	public Void ReportProgress(Int32 percentProgress) { }
	// RVA: 0x63b0c28 VA: 0x75989c8c28
	public Void ReportProgress(Int32 percentProgress, Object userState) { }
	// RVA: 0x63b0d28 VA: 0x75989c8d28
	public Void RunWorkerAsync() { }
	// RVA: 0x63b0d30 VA: 0x75989c8d30
	public Void RunWorkerAsync(Object argument) { }
	// RVA: 0x63b0f48 VA: 0x75989c8f48
	public Void add_RunWorkerCompleted(RunWorkerCompletedEventHandler value) { }
	// RVA: 0x63b0fe4 VA: 0x75989c8fe4
	public Void remove_RunWorkerCompleted(RunWorkerCompletedEventHandler value) { }
	// RVA: 0x63b1080 VA: 0x75989c9080
	public Boolean get_WorkerReportsProgress() { }
	// RVA: 0x63b1088 VA: 0x75989c9088
	public Void set_WorkerReportsProgress(Boolean value) { }
	// RVA: 0x63b1094 VA: 0x75989c9094
	public Boolean get_WorkerSupportsCancellation() { }
	// RVA: 0x63b109c VA: 0x75989c909c
	public Void set_WorkerSupportsCancellation(Boolean value) { }
	// RVA: 0x63b10a8 VA: 0x75989c90a8
	private Void WorkerThreadStart(Object argument) { }
	// RVA: 0x63b1230 VA: 0x75989c9230
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x63b1234 VA: 0x75989c9234
	private Void <RunWorkerAsync>b__27_0(Object arg) { }
}
```