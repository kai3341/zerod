# 1.1.3
- Fix double rm of pidfile without `RESTART=1`
- Fix `returncode` logging
- Update README

# 1.1.2
- Unify and fix `stop` command. Yes, again
- Reduce command nesting level
- Also log zerod's messages
- Log `${CMD}`'s stops with returncodes

# 1.1.1
- Fix incorrect `stop` when `RESTART=1`

# 1.1.0
- Total rework PID control
- Small environment variables changes

# 1.0
- Initial commit
