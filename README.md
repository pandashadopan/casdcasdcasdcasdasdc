lein test :only waiter.auth.jwt-test/test-jwt-cache-maintainer

FAIL in (test-jwt-cache-maintainer) (jwt_test.clj:179)
expected: (wait-for (fn [] (= (take counter jwks-data) (:keys (query-state-fn)))) :interval 5 :timeout 25 :unit-multiplier 1)
  actual: (not (wait-for #object[waiter.auth.jwt_test$fn__30262$fn__30289$fn__30291$fn__30292$fn__30293 0x16f1c904 "waiter.auth.jwt_test$fn__30262$fn__30289$fn__30291$fn__30292$fn__30293@16f1c904"] :interval 5 :timeout 25 :unit-multiplier 1))

lein test :only waiter.auth.jwt-test/test-jwt-cache-maintainer

FAIL in (test-jwt-cache-maintainer) (jwt_test.clj:179)
expected: (wait-for (fn [] (= (take counter jwks-data) (:keys (query-state-fn)))) :interval 5 :timeout 25 :unit-multiplier 1)
  actual: (not (wait-for #object[waiter.auth.jwt_test$fn__30262$fn__30289$fn__30291$fn__30292$fn__30293 0x430fb6ec "waiter.auth.jwt_test$fn__30262$fn__30289$fn__30291$fn__30292$fn__30293@430fb6ec"] :interval 5 :timeout 25 :unit-multiplier 1))
