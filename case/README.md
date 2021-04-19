# Regular Expression ???

### Example
```perl
JIRA issue key ( EX : CI-100, NOWRAP-8670, JENKINS-200, SPACE : 1 )
my $target = 'NOWRAP-8670 : tested code commited';
my $match = $target =~ /([A-Z]*)-([1-9]?[0-9]*)/g;
```
