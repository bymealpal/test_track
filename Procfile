web: bundle exec puma -w ${WEB_CONCURRENCY:-1} -t ${RAILS_MAX_THREADS:-5}:${RAILS_MAX_THREADS:-5} -p ${PORT:-3000} -e ${RACK_ENV:-development}
worker: bundle exec rake jobs:work
