# ARAnalytics

## Version 1.0

*   Fix is done in - (void)logTimingEvent:(NSString *)event
    withInterval:(NSNumber *)interval properties:(NSDictionary *)properties
    function. At first getting category from properties dictionary, and if
    there is no category set, uses "default" keyword.
 
