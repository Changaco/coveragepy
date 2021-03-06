
.. code::

    $ coverage report --help
    Usage: coverage report [options] [modules]

    Report coverage statistics on modules.

    Options:
      --contexts=REGEX1,REGEX2,...
                            Only display data from lines covered in the given
                            contexts. Accepts Python regexes, which must be
                            quoted.
      --fail-under=MIN      Exit with a status of 2 if the total coverage is less
                            than MIN.
      -i, --ignore-errors   Ignore errors while reading source files.
      --include=PAT1,PAT2,...
                            Include only files whose paths match one of these
                            patterns. Accepts shell-style wildcards, which must be
                            quoted.
      --omit=PAT1,PAT2,...  Omit files whose paths match one of these patterns.
                            Accepts shell-style wildcards, which must be quoted.
      --precision=N         Number of digits after the decimal point to display
                            for reported coverage percentages.
      --sort=COLUMN         Sort the report by the named column: name, stmts,
                            miss, branch, brpart, or cover. Default is name.
      -m, --show-missing    Show line numbers of statements in each module that
                            weren't executed.
      --skip-covered        Skip files with 100% coverage.
      --no-skip-covered     Disable --skip-covered.
      --skip-empty          Skip files with no code.
      --debug=OPTS          Debug options, separated by commas. [env:
                            COVERAGE_DEBUG]
      -h, --help            Get help on this command.
      --rcfile=RCFILE       Specify configuration file. By default '.coveragerc',
                            'setup.cfg', 'tox.ini', and 'pyproject.toml' are
                            tried. [env: COVERAGE_RCFILE]

