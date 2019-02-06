```
% esy
% esy b dune build
% esy b dune build bin/rehp_test.bc.php
% esy b dune build bin/rehp_test.bc.php
% esy vim '#{self.target_dir}/default/bin/rehp_test.bc.php'
```

TODO

- Need proper dune rules: first invocation now fails because not all
  dependencies are compiled, second invocation succeeds though.

- Example on how to run resulted php. This
	```
	php -f '#{self.target_dir}/default/bin/rehp_test.bc.php'
	```
	now fails.
