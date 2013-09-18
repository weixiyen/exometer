

# Module exometer_probe_stackdriver #
* [Function Index](#index)
* [Function Details](#functions)

__Behaviours:__ [`exometer_entry`](exometer_entry.md), [`exometer_probe`](exometer_probe.md).
<a name="index"></a>

## Function Index ##


<table width="100%" border="1" cellspacing="0" cellpadding="2" summary="function index"><tr><td valign="top"><a href="#connect-1">connect/1</a></td><td></td></tr><tr><td valign="top"><a href="#delete-3">delete/3</a></td><td></td></tr><tr><td valign="top"><a href="#get_value-3">get_value/3</a></td><td></td></tr><tr><td valign="top"><a href="#new-3">new/3</a></td><td></td></tr><tr><td valign="top"><a href="#probe_code_change-3">probe_code_change/3</a></td><td></td></tr><tr><td valign="top"><a href="#probe_get_value-1">probe_get_value/1</a></td><td></td></tr><tr><td valign="top"><a href="#probe_handle_call-3">probe_handle_call/3</a></td><td></td></tr><tr><td valign="top"><a href="#probe_handle_cast-2">probe_handle_cast/2</a></td><td></td></tr><tr><td valign="top"><a href="#probe_handle_info-2">probe_handle_info/2</a></td><td></td></tr><tr><td valign="top"><a href="#probe_init-3">probe_init/3</a></td><td></td></tr><tr><td valign="top"><a href="#probe_reset-1">probe_reset/1</a></td><td></td></tr><tr><td valign="top"><a href="#probe_sample-1">probe_sample/1</a></td><td></td></tr><tr><td valign="top"><a href="#probe_setopts-2">probe_setopts/2</a></td><td></td></tr><tr><td valign="top"><a href="#probe_terminate-1">probe_terminate/1</a></td><td></td></tr><tr><td valign="top"><a href="#probe_update-2">probe_update/2</a></td><td></td></tr><tr><td valign="top"><a href="#reset-3">reset/3</a></td><td></td></tr><tr><td valign="top"><a href="#sample-3">sample/3</a></td><td></td></tr><tr><td valign="top"><a href="#setopts-4">setopts/4</a></td><td></td></tr><tr><td valign="top"><a href="#test-1">test/1</a></td><td></td></tr><tr><td valign="top"><a href="#test-2">test/2</a></td><td></td></tr><tr><td valign="top"><a href="#update-4">update/4</a></td><td></td></tr></table>


<a name="functions"></a>

## Function Details ##

<a name="connect-1"></a>

### connect/1 ###

`connect(Opts) -> any()`


<a name="delete-3"></a>

### delete/3 ###

`delete(Name, Type, Ref) -> any()`


<a name="get_value-3"></a>

### get_value/3 ###

`get_value(Name, Type, Ref) -> any()`


<a name="new-3"></a>

### new/3 ###

`new(Name, Type, Options) -> any()`


<a name="probe_code_change-3"></a>

### probe_code_change/3 ###

`probe_code_change(X1, St, X3) -> any()`


<a name="probe_get_value-1"></a>

### probe_get_value/1 ###

`probe_get_value(St) -> any()`


<a name="probe_handle_call-3"></a>

### probe_handle_call/3 ###

`probe_handle_call(Req, From, St) -> any()`


<a name="probe_handle_cast-2"></a>

### probe_handle_cast/2 ###

`probe_handle_cast(Msg, St) -> any()`


<a name="probe_handle_info-2"></a>

### probe_handle_info/2 ###

`probe_handle_info(Msg, St) -> any()`


<a name="probe_init-3"></a>

### probe_init/3 ###

`probe_init(Name, Type, Opts) -> any()`


<a name="probe_reset-1"></a>

### probe_reset/1 ###

`probe_reset(St) -> any()`


<a name="probe_sample-1"></a>

### probe_sample/1 ###

`probe_sample(St) -> any()`


<a name="probe_setopts-2"></a>

### probe_setopts/2 ###

`probe_setopts(Opts, St) -> any()`


<a name="probe_terminate-1"></a>

### probe_terminate/1 ###

`probe_terminate(St) -> any()`


<a name="probe_update-2"></a>

### probe_update/2 ###

`probe_update(Value, St) -> any()`


<a name="reset-3"></a>

### reset/3 ###

`reset(Name, Type, Ref) -> any()`


<a name="sample-3"></a>

### sample/3 ###

`sample(Name, Type, Ref) -> any()`


<a name="setopts-4"></a>

### setopts/4 ###

`setopts(Name, Opts, Type, Ref) -> any()`


<a name="test-1"></a>

### test/1 ###

`test(Opts) -> any()`


<a name="test-2"></a>

### test/2 ###

`test(Status, Opts) -> any()`


<a name="update-4"></a>

### update/4 ###

`update(Name, Value, Type, Ref) -> any()`

